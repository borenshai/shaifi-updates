# shaifi-updates

Signed over-the-air updates for the ShaiFi app layer. Contains only app code (HTML/JS) — no personal or financial data.
Each `web/<build>.html` is listed in `latest.json` with its SHA-256 and an Ed25519 signature; the app rejects anything not signed by its key.
