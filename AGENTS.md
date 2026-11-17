# shearcut-site

Public GitHub Pages site for ShearCut (the app lives in `~/code/ClipForge`).
Served at https://hxxdini.github.io/shearcut/ from the `main` branch root.

- `client.json` is the OAuth **client ID metadata document** ElevenLabs uses to identify ShearCut
  when a user connects their ElevenLabs account. Its URL *is* the client_id. Don't move or rename it,
  and keep `redirect_uris` in sync with the app's callback (`clipforge_ui.py`, port 8765).
- `index.html` is a placeholder for the future landing page.
