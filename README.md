# Affiliate Landing Page (GitHub Pages)

Diese Landing Page ist als **statische HTML-Seite** gedacht und funktioniert direkt auf **GitHub Pages**.

## Deployment auf GitHub Pages

Diese Anleitung nutzt **GitHub Actions**.

1. Repository auf GitHub pushen.
2. In **Settings → Pages**:
   - **Source**: `GitHub Actions`
3. Speichern. Der Workflow veröffentlicht die Seite automatisch.

Nach dem Build ist die Seite unter der angegebenen Pages-URL erreichbar.

## Hinweise

- Die Datei `index.html` liegt im Repository-Root, was GitHub Pages standardmäßig als Startseite nutzt.
- Die Datei `.nojekyll` deaktiviert Jekyll-Processing, damit alle Assets/Dateien unverändert ausgeliefert werden.
