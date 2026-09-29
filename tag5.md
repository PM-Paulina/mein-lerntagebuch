# Tag 5 – .gitignore

Datum: 30.09.2026

## Was habe ich gelernt?

- In der Datei `.gitignore` stehen Dateien und Ordner, die Git nicht speichern soll.
- Typische Beispiele sind Einstellungsordner vom Editor (`.vscode/`) oder Systemdateien von Windows (`Thumbs.db`).
- Dateien, die in `.gitignore` stehen, tauchen bei `git status` nicht mehr auf.

## Welches Problem hatte ich?

- Der Dateiname beginnt mit einem Punkt. Im Explorer von Windows ist so eine Datei manchmal schwer zu sehen.

## Wie habe ich es gelöst?

- Ich habe die Datei in VS Code angelegt und mit `git status` geprüft, dass Git sie erkennt.
