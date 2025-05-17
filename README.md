# SDG-Analyse in München

Dieses Repository enthält eine Analyse der Sustainable Development Goals (SDGs) der UN im Kontext der Stadt München, erstellt im Rahmen der Modularbeit "Datenaufbereitung und Visualisierung" an der Hochschule München.

## Repository klonen

Um dieses Repository zu klonen und lokal zu verwenden, führen Sie folgenden Befehl aus:

```bash
git clone https://github.com/Aesha252/SDG-Analyse-in-Muenchen.git
cd SDG-Analyse-in-Muenchen
```

## Ergebnisse ansehen

1. **HTML-Report direkt ansehen:**
   - Die HTML-Datei im Repository enthält den kompletten Report mit allen Visualisierungen und Ergebnissen
   - Da die HTML-Datei aufgrund ihrer Größe nicht direkt auf GitHub angezeigt werden kann (Fehlermeldung: "Sorry about that, but we can't show files that are this big right now"), laden Sie diese bitte herunter und öffnen Sie sie lokal in einem Browser:
     - Klicken Sie auf die HTML-Datei
     - Klicken Sie auf den "Raw"-Button
     - Speichern Sie die Seite über Ihren Browser (Rechtsklick → "Speichern unter...")
     - Öffnen Sie die gespeicherte Datei lokal

2. **R Markdown ausführen:**
   ```r
   # Benötigte Pakete installieren
   source("DataVizMAinstall.R")
   
   # Mit RStudio die .Rmd-Datei öffnen und ausführen
   # oder über die Kommandozeile:
   rmarkdown::render("DataVizMA.Rmd")
   ```

## Aufgabenstellung

Der Report bearbeitet folgende Aufgaben:

1. **Hypothesengenerierung & Datenbeschaffung:** Analyse ausgewählter SDG-Ziele für München mit Daten von [opendata.muenchen.de](https://opendata.muenchen.de/)

2. **Datenaufbereitung:** Einlesen und Bereinigung der Datensätze

3. **Überblick Datensatz:** Zusammenfassende Statistiken und Visualisierungen

4. **Ausreißeranalyse:** Identifikation und Umgang mit extremen Werten

5. **Anonymisierung:** Betrachtung von Datenschutzaspekten

6. **Info-Grafik:** Visualisierung zeitlicher Entwicklungen oder räumlicher Verteilungen

7. **Bonus:** Interaktive Visualisierungen

## Verwendete Datensätze

Die für die Analyse verwendeten Datensätze befinden sich im `data/`-Ordner und stammen hauptsächlich vom Open Data Portal der Stadt München.

## Kontakt

Bei Fragen zum Repository oder zur Analyse können Sie einen Issue im Repository erstellen oder direkt über GitHub Kontakt aufnehmen.
