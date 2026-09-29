# Tag 3 – Feature-Branch, Pull Request & CI

Datum: 30.09.2026

## Was habe ich gelernt?

- `git switch -c feature/ci-workflow` legt einen neuen Branch an und wechselt direkt dorthin.
- Auf einem Branch kann ich etwas ausprobieren, ohne `main` zu verändern.
- Ein Pull Request ist eine Anfrage, die Änderungen aus einem Branch in `main` zu übernehmen.
- Ein CI-Workflow (GitHub Actions) prüft meinen Code automatisch bei jedem Push und Pull Request.

## Welches Problem hatte ich?

- GitHub findet Workflows nur im Ordner `.github/workflows`. Meine Datei `ci.yml` lag im Hauptordner.

## Wie habe ich es gelöst?

- Ordner angelegt mit `mkdir .github\workflows` und die Datei mit `mv` verschoben.
- Branch gepusht, auf GitHub den Pull Request geöffnet, auf den grünen Haken gewartet und gemergt.
- Danach lokal mit `git switch main` und `git pull` wieder auf den neuesten Stand gebracht.
