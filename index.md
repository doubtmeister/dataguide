# Einleitung

Dieser Datenkompass richtet sich in erster Linie an Menschen, die Interesse an Datenauswertung haben, aber auf dem Gebiet epidemiologischer Daten neu sind.
Hier soll also eine Übersicht der verfügbaren Primärquellen gegeben werden. Zudem gibt es einige Fallstricke, beispielsweise widersprüchlich
wirkende Daten und schwammige Definitionen, die bekannt sein sollten.

Diese Seite ist ausdrücklich als Mitmach-Projekt gedacht! Es gibt zu viele "dunkle Ecken", alsdass ein Mensch jedes Detail kennen könnte.
Daher bin ich für jede helfende Hand dankbar; mehr dazu am Ende dieser Seite.

***Dies ist nur ein Grundgerüst. Der Inhalt folgt nach und nach...***

# Primärquellen

Das Wichtigste zuerst: Die Primärquellen, die uns in Deutschland zur Verfügung stehen.

Zu vielen Datensätzen gibt es weitergehende Anmerkungen, die entsprechend verlinkt sind.

## Robert-Koch-Institut (RKI)

Die Gesamtübersicht aller Informationen zu Corona findet sich [hier](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/nCoV.html).

Zudem gibt es ein Daten-Dashboard unter https://corona.rki.de/ (teils hilfreiche Beschreibungen!)

### Berichte

Das RKI veröffentlicht tage- und wochenweise diverse Berichte.
Übersichtsseite: https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/Situationsberichte/Gesamt.html

- Situationsbericht (täglich)
- Trends (täglich)
- Omikron-Fälle (täglich)
- Wochenbericht

### Verarbeitungsfähige Daten

Daten, die man tatsächlich selbst auswerten kann, finden sich hier:

#### Github

Das [Github Repository des RKI](https://github.com/robert-koch-institut) bietet neben den Datensätzen auch sehr ausführliche
Beschreibungen der Daten, die hilfreich zum Verstehen der Meldewege und Aufbereitungen sind. Die meisten Datensätze liegen als CSV vor.

- Impfungen (diese Daten zeigt auch das https://impfdashboard.de des Gesundheitsministeriums)
  - Zeitreihe nach Bundesland (Impfstoff, Impfserie)
  - Zeitreihe nach Landkreis (mit Altersgruppen!)
  - Übersicht der Impfquoten
- Sequenz- und zugehörige Metadaten
- Hospitalisierungen
  - Zeitreihe nach Bundesland, Altersgruppe, Fallzahlen und *aktualisierter* Inzidenz
  - Zeitreihe nach Bundesland, Altersgruppe und diversen Werten zu Inzidenzen (fixiert, aktualisiert, adjustiert; dazu siehe unten)
- Infektionen: Zeitreihe nach Landkreis, Altersgruppe mit Werten zur Anzahl Fälle / Todesfälle / Genesene (Achtung: "große" Datei)

#### Sonstige Datensammlungen

Mundgerecht als Excel:
- Impfdaten (täglich), verlinkt auf der [Übersicht zum Impfquotenmonitoring](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/Daten/Impfquoten-Tab.html)
- tägliche oder wöchentliche Aufbereitung der o.a. Daten als Excel, Liste hier unter [Daten zum Download](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/nCoV.html#doc13490882bodyText12); außerdem erwähnenswert:
  - Fälle nach Zuordnung zu Ausbrüchen (Cluster von >=2 Fällen) *TODO*
  - Todesfälle nach Sterbedatum und 10er-Altersgruppen (feinere Abstufung als im Infektionsdatensatz)
  - oft sind zusätzliche Informationen enthalten (z.B. Anteil mit Angabe zu Symptomen etc.)
  - Nowcasting / Schätzung von *R*
  - Testzahlen
  - Varianten
  - *TODO* (alle mal sichten)


## DIVI e.V.
...

## Statistisches Bundesamt (destatis)
...

## Paul-Ehrlich-Institut (PEI)
...

## Institut für das Entgeltsystem im Krankenhaus (InEK)
...

# Grundsätzliches

## Definitionen

(Fälle, Inzidenz, Impfstatus, Nachmeldungen, unterschiedliche Hosp'inzidenzen, ...)

# Automatisierung
...

# Kontakt & Feedback

Direkt über die Github-Seite können *Issues* und *Pull requests* geöffnet werden.

Ansonsten gerne [bei Twitter](https://twitter.com/doubtmeister) anschreiben; DMs sind offen.
