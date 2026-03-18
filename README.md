# tech-demo-support-Bot

Dies ist eine kleine statische Website Demo für einen AI Support Bot.

## Deployment (GitHub Pages)

1) Stelle sicher, dass du im Hauptbranch (`main`) bist.
2) Committe Dateien:
   ```bash
git add index.html README.md
git commit -m "Add AI support bot demo"
git push origin main
```
3) Aktiviere GitHub Pages in den Repository-Einstellungen:
   - Settings -> Pages -> Branch: `main` -> Ordner: `/ (root)` -> Save
4) Öffne die Website unter `https://<dein-github-user>.github.io/tech-demo-support-Bot/`.

## Hinweise
- Falls der Chat keine Antwort bekommt, überprüfe `CONFIG.webhookUrl` im `index.html`.
- Bei CORS-Fehlern musst du das Webhook-Backend so konfigurieren, dass es Browser-Anfragen erlaubt.
