# Mein Lerntagebuch

Sieben Tage, sieben Einträge: Hier dokumentiere ich, was ich im
**Digitale-Leute Vibe Coding Bootcamp** über Git, GitHub und die
Kommandozeile lerne.

Jeder Eintrag beantwortet drei Fragen:

1. Was habe ich gelernt?
2. Welches Problem hatte ich?
3. Wie habe ich es gelöst?

## Einträge

| Tag | Eintrag | Thema |
| --- | --- | --- |
| 1 | [Tag 1](tag1.md) | Repository anlegen, erster Push |
| 2 | [Tag 2](tag2.md) | Feature-Branch & Pull Request |
| 3 | [Tag 3](tag3.md) | GitHub Pages |
| 4 | [Tag 4](tag4.md) | _folgt_ |
| 5 | [Tag 5](tag5.md) | _folgt_ |
| 6 | [Tag 6](tag6.md) | _folgt_ |
| 7 | [Tag 7](tag7.md) | _folgt_ |

## Was in diesem Repository steckt

- `tag1.md` bis `tag7.md` – ein Eintrag pro Tag, ein Commit pro Tag
- `.github/workflows/ci.yml` – prüft bei jedem Push und Pull Request,
  ob alle Markdown-Dateien sauber formatiert sind
- `_config.yml` – Einstellungen für die GitHub-Pages-Webseite

## Git-Befehle, die ich hier benutze

```bash
git status                     # Was hat sich geändert?
git add tag2.md                # Datei für den nächsten Snapshot vormerken
git commit -m "Tag 2: ..."     # Snapshot speichern
git push                       # Snapshot zu GitHub hochladen
git switch -c feature/xyz      # Neuen Branch anlegen und wechseln
git log --oneline --graph      # Verlauf als Baum anzeigen
```
