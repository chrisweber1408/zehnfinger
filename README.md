# Zehnfinger – 10-Finger-Schreiben lernen (QWERTZ)

Eine moderne, ablenkungsfreie Web-App zum Erlernen des 10-Finger-Schreibsystems auf dem deutschen QWERTZ-Layout. Läuft vollständig im Browser – ohne Anmeldung, ohne Tracking, ohne Build-Prozess.

**[▶ Jetzt ausprobieren](https://chrisweber1408.github.io/zehnfinger/)**

## Features

- **16 aufbauende Lektionen** – von der Grundstellung (ASDF JKLÖ) über alle Buchstaben, Umlaute und ß bis zu Großbuchstaben, Zahlen, Satzzeichen und ganzen Sätzen
- **Visuelle QWERTZ-Tastatur** – die nächste Taste wird hervorgehoben, Farbcodierung und Hand-Grafik zeigen den richtigen Finger (inkl. Hinweis auf die gegenüberliegende Umschalttaste)
- **Live-Feedback** – richtige Zeichen grün, Fehler rot, optional mit Ton; Fehler blockieren nicht und lassen sich mit Backspace korrigieren
- **Auswertung in Echtzeit** – Anschläge pro Minute (APM), Wörter pro Minute (WPM), Genauigkeit, Zeit und Fehlerzahl; nach jeder Übung mit Sternebewertung und Problemtasten
- **Lernfortschritt** – freigeschaltete Lektionen und Bestwerte werden lokal im `localStorage` gespeichert
- **Dark Mode**, responsives Layout und Unterstützung für Bildschirmtastaturen

## Bedienung

| Aktion | Taste |
| --- | --- |
| Übung neu starten | `Esc` |
| Fehler korrigieren | `Backspace` |
| Nächste Lektion (im Ergebnisfenster) | `Enter` |

Jede abgeschlossene Übung schaltet die nächste Lektion frei – unabhängig von der Genauigkeit. Sterne zeigen, wie genau du getippt hast (★ ab 90 %, ★★ ab 95 %, ★★★ ab 98 %).

## Installation & Hosting

Die gesamte App besteht aus einer einzigen Datei: `index.html`.

- **Lokal:** `index.html` einfach im Browser öffnen.
- **GitHub Pages:** Datei ins Repository legen, dann unter *Settings → Pages* den Branch `main` und den Ordner `/ (root)` auswählen.

## Technik

Reines HTML, CSS und JavaScript – keine Frameworks, keine Abhängigkeiten. Der Fortschritt bleibt ausschließlich im Browser des Nutzers.

## Lizenz

MIT
