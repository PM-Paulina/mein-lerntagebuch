# Tag 2 – Kaputte README reparieren

Datum: 30.09.2026

## Was habe ich gelernt?

- GitHub zeigt die `README.md` automatisch als Startseite vom Repository an.
- Jeder Commit ist ein Snapshot. Einen Fehler repariere ich einfach mit einem neuen Commit.
- `echo "..." >> README.md` hängt in PowerShell Text in einer anderen Kodierung (UTF-16) an.

## Welches Problem hatte ich?

- Nach dem ersten Push war meine README auf GitHub nur noch ein einziger Textblock ohne Formatierung.
- Ich hatte zusätzlich die Befehle aus der GitHub-Anleitung ausgeführt. Der `echo`-Befehl hat die Datei kaputt gemacht.

## Wie habe ich es gelöst?

- Ich habe die README durch eine saubere Version ersetzt.
- Mit `git status` geprüft, was sich geändert hat, dann `git add`, `git commit` und `git push`.
