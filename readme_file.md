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
   - Die HTML-Datei `DataVizMA.html` enthält den kompletten Report mit allen Visualisierungen und Ergebnissen.
   - Wenn die Datei aufgrund der Größe nicht direkt auf GitHub angezeigt werden kann, laden Sie sie herunter und öffnen Sie sie lokal in einem Browser.

2. **R Markdown ausführen (für R-Nutzer):**
   ```r
   # Benötigte Pakete installieren
   source("DataVizMAinstall.R")
   
   # Mit RStudio die .Rmd-Datei öffnen und ausführen
   # oder über die Kommandozeile:
   rmarkdown::render("DataVizMA.Rmd")
   ```

3. **Jupyter Notebook ausführen (für Python-Nutzer):**
   ```bash
   # Benötigte Pakete installieren
   pip install -r requirements.txt
   
   # Notebook starten
   jupyter notebook DataVizMA.ipynb
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

## Technische Hinweise

- Bei Problemen mit Dateipfaden passen Sie bitte den Pfad zum Datenordner in der Hauptdatei an
- Die Analyse wurde mit [R/Python-Version] erstellt
- Bei Anzeigeproblemen der HTML-Datei auf GitHub laden Sie diese herunter und öffnen Sie lokal
