# Slozzy

Faultier-Reaktionsspiel fuer iOS. Das Spiel ist eine Web-App in `www/index.html`, verpackt mit Capacitor.

## Lokal spielen (Windows)

    npm install
    npm start

Der Browser oeffnet sich auf http://localhost:5173.

## iOS-Build

Das iOS-Projekt wird nicht auf diesem Rechner erzeugt. Codemagic baut es bei jedem Lauf frisch nach `codemagic.yaml` und laedt das Ergebnis zu TestFlight hoch.

- Bundle-ID: `de.grzesiak.slozzy` (steht in `capacitor.config.json` und `codemagic.yaml`)
- Icon und Startbildschirm: Vorlagen in `assets/`
