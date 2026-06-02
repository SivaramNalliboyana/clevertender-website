# clevertender-site

Marketing-Landingpage für CleverTender. Reines statisches HTML, kein Build-Step.

## Struktur

- `index.html`: Startseite
- `impressum.html`: Impressum
- `datenschutz.html`: Datenschutzerklärung
- `CleverTender_Logo-20260529.png`: Logo

## Lokal anschauen

Einfach `index.html` im Browser öffnen, oder einen kleinen HTTP-Server starten:

```
npx serve .
# oder
python -m http.server 8000
```

## Deploy

Auto-Deploy via Vercel. Jeder Push auf `main` deployed automatisch.
