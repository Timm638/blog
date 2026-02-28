---
layout: post
title:  "2. Spezitasting"
tags: tasting
lang: de
page_id: spezi_2
---

Das Spezial-Getränk, umgangssprachlich auch bekannt als "Spezi", "Cola-Mix", "Gwasch", "Kalter Kaffee" oder "Moorwasser", ist das vermutlich berühmteste alkoholfreie Getränk in Bayern. Da ist es nicht verwunderlich, dass Leute sich die wissenschaftliche Frage stellen, welche die beste ist. Welches Getränk schmeckt am fruchtigsten? Wo ist das Kohlensäureniveau am optimalsten? Welche Spezi ist resistent gegen das Abstehen? 
Zur Klärung dieser wissenschaftlichen Frage habe ich ein [Spezitasting](https://zapf.wiki/SoSe25_AK_Spezi-/Mate-Tasting) auf der [ZaPF](https://zapf.wiki/SoSe25) (Zusammenkunft aller Physikfachschaften) durchgeführt.

# Zu bewertende Spezis

Im lokalen Getränkemarkt wurden 10 Spezisorten ausgesucht, die zumindestens eine regionale Bekanntheit aufweisen:

| Name            | Brauerei                  | Link                                         |
| --------------- | ------------------------- | -------------------------------------------- |
| Spezi Original  | Spezi Markenzentrale GmbH | [Link](https://www.spezi.com/spezi-original) |
| Cola-Mix        | Pyraser Landbrauerei GmbH & Co. KG | [Link](https://www.pyraser.de/sortiment/getraenke/cola-mix) |
| Paulaner Spezi  | Paulaner Brauerei Gruppe GmbH & Co. KGaA | [Link](https://www.paulaner.de/produkte/spezi/spezi/) |
| Flötzinger Cola Mix  | Flötzinger Brauerei Franz Steegmüller GmbH & Co. KG | [Link](https://www.floetzinger.de/produkt/floetzinger-cola-mix) |
| Mezzo Mix  | Coca-Cola Europacific Partners Deutschland GmbH | [Link](https://www.coca-cola.com/de/de/brands/brand-mezzo-mix) |
| Cola-Mix  | Brauerei Loscher GmbH & Co. KG | [Link](https://brauerei-loscher.de/produkt/cola-mix/) |
| Cola-Mix  | Andreas Leikeim GmbH & Co. KG | [Link](https://www.leikeim.de/#unser-sortiment) |
| Mexi Cola-Mix  | FRANKEN BRUNNEN GmbH & Co. KG | [Link](https://frankenbrunnen.de/limonaden-suessgetraenke/mexi-cola-mix-limonade) |
| Libella Cola Mix  | ADM WILD Europe GmbH & Co. KG | [Link](https://www.libella.de/unsere-produkte/cola-mix/) |
| DEIT Cola-Mix  | DrinkStar GmbH | [Link](https://www.deit.de/deit-sortiment/deit-cola-mix/) |

# Struktur der Abfrage

![](assets/img/2025-05-01-spezitasting/umfrage.png)

Es wurde [SoSciSurvey](https://www.soscisurvey.de/) verwendet, um eine Umfrage aufzusetzen und durchzuführen. Teilnehmern wurde ein QR-Code zu der Website per Beamer im Hörsaal gezeigt. Die Gesamtbewertung ist dabei ein eigener Wert, welche die Teilnehmer angeben konnten, und ist **nicht** die gemittelt aus den anderen Bewertungen. Die Spezi wurde blind verteilt.
Bei jeder Spezi haben mindestens 17 Personen bzw. max 20 Personen abgestimmt, da während den 1,5 Stunden Teilnehmer dazukam bzw. wieder gingen.
Die Auswertung sowie die Visualisierung dieser wurde Python mit [seaborn](https://seaborn.pydata.org/), [matplotlib](https://matplotlib.org/) und [pandas](https://pandas.pydata.org/) verwendet.


# Auswertung

#### Farbe
![](assets/img/2025-05-31-spezitasting/spezi_farbe.png)

Die Probanden bewerteten die Farben der Riegele Spezi & der Leikeim Spezi deutlich besser als die anderen Spezis. Keine Farbe wurde durchschnittlich schlechter als 3.0 bewertet .

#### Geruch
![](assets/img/2025-05-01-spezitasting/spezi_geruch.png)

Das Flötzinger sowie das Frankenbrunnen stechen durch ihren Geruch hervor. Das Flötzinger fällt vermutlich durch den hohen Anteil an Orangensaft auf. Paulaner & Riegele Spezi bilden hierbei das Mittelfeld.

#### Geschmack
![](assets/img/2025-05-01-spezitasting/spezi_geschmack.png)

Im Geschmack ist eindeutig zu sehen, dass die Personengruppe nicht korrupt ist: Die Spezi von Coca Cola namens "Mezzomix", welche in meinen Kreisen die schlechteste etablierte Spezi ist, wurde auch als schlechteste eingestuft. Diet Zuckerfrei sowie das Loscher-Cola-Mix sind sehr negativ durch ihren abweichenden Geschmack aufgefallen. Die Original Spezi hat hierbei die beste Bewertung erhalten, auch wenn der Vergleich mit allen anderen Spezis marginal ist. Die Spezi von Frankenbrunnen ist überraschenderweise Zweiter und ist somit höher platziert als die Paulaner Spezi.

#### Kohlensäure
![](assets/img/2025-05-01-spezitasting/spezi_ks.png)

Ein eindeutiges Muster war nicht zu erkennen, auch nicht zwischen den in Plastikflaschen gelagerte Mezzo Mix & Deit und den restlichen Glasflaschen-Spezis.

#### Gesamtbewertung
![](assets/img/2025-05-01-spezitasting/spezi_gesamt.png)



# Fazit
![](assets/img/2025-05-01-spezitasting/spezi_alles.png) 

| Platzierung |	Spezi |
| ----------- | ----- |
| 1. Platz    | Blaue Spezi / Riegele |
| 2. Platz    |	Flötzinger Cola-Mix |
| 3. Platz    |	Paulaner Spezi |

Letztendlich finden sich die beiden bekanntestens Spezi von Riegele sowie Paulaner auf der Siegertreppe. Das Flötzinger so stark punkten konnte, liegt am hohen Orangen-Anteil. Daraufhin folgt Frankenbrunnen, Libella, Leikeim und Pyraser in dieser Reihenfolge. Die schlechtesten Spezis sind die von Loscher, Deit zuckerfrei (wobei dies zuckerfrei ist und eigentlich mit anderen zuckerfreien Spezis verglichen müsste) und mit relativ weiten Abstand Mezzo-Mix. 

# Organisatorisches

Spezi wurde verteilt, indem diese auf der untersten Ebene der Hörsaal verdeckt abgefüllt wurde und die Plastikbecher vergeben wurde.
Wir hatten ~150 Plastikbecher, die gegen Ende hin ausgingen, da wir jede Sorte pro Person in ein Becher ausgegeben haben und diese nicht wiederverwendet haben.
Umfrage war nervig aufzusetzen, da man sich durch alle Seiten durchklicken musste wenn man mittendrin kam. SoSciSurvey ist aber sehr solide um spontan Sachen während der Umfrage hinzuzufügen. Davor am besten die Getränkereihenfolge festlegen, um das in der Umfrage zu vermerken (damit da "Paulaner Spezi" statt "Spezi 1" dasteht).
Der verwendete (mittlerweile [vermutlich gesperrte](https://www.ardmediathek.de/video/extra-3/marode-uni-in-erlangen/ndr/Y3JpZDovL25kci5kZS8yODBlYjAyMy0yMmViLTQ5MzQtODY2OC1lODBkNzE0ODAwNmE)) Hörsaal ungünstig, um Spezi im Geheimen abzufüllen (–> Dezentraleres Tasting-Konzept).
Das Tasting wurde um 8:00 frühs veranstaltet, was eine sehr memewürdige Zeit ist. Mehr als die Hälfte der Leute im Tasting haben angegeben, deswegen früher aufgestanden zu sein. 

#### Ideen für zukünftige Spezitastings  
- Zweidimensionaler Geschmacksmatrix für Spezi mit Achsen "Cola" & "Orange"
- RGB-Farbcodes abfragen
- Objektive Bewertung des Kohlensäuregehalts, um diesen mit subjektive Kohlensäurebewertung zu vergleichen
- Weiterentwicklung des Konzepts durch [dezentraleres Tasting ohne Geheimhaltungsanspruch]({% link posts/spezitasting-3 %}): Jeder bringt 2 Flaschen mit, eine Umfrage wo man selber pro probierte Sorte Name des Spezi mit Bewertung einträgt