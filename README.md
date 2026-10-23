# Börsenkalender – öffentliche Datenquellen

## Installation/Update auf GitHub Pages
1. Entpacke dieses ZIP.
2. Öffne dein bestehendes GitHub-Repository.
3. Add file → Upload files.
4. Lade `index.html`, `manifest.webmanifest`, `sw.js` und `icon.svg` hoch und bestätige Commit changes.
5. Warte auf GitHub Pages und lade die Website auf dem Handy neu. Falls eine alte Version erscheint, schließe die App vollständig und öffne sie erneut.

## Datenquellen und Einschränkungen
- SmarterDividends: öffentlich zugängliche, schlüssellose Dividenden-API für erfasste US-gelistete Aktien. Quelle: https://smarterdividends.com/dividend-api. Link zur Quelle wird angezeigt. API-Antworten können ihr Format ändern.
- Tigzig/Yahoo-derived calendar: https://yfin-h.tigzig.com/v1/redoc. Drittanbieter, kein offizieller Yahoo-Dienst. Verfügbarkeit/CORS/Abdeckung nicht garantiert.
- Diese Version ruft Quellen direkt aus dem Browser ab. Browser-CORS- oder Anbieteränderungen können Abrufe verhindern.
- Hauptversammlungen werden nicht automatisch erfasst. Keine zuverlässige kostenlose globale Quelle für alle vier Terminarten gefunden.
- Aktienwatchlist und Termine werden lokal im Browser gespeichert; sie werden nicht zwischen Geräten synchronisiert.
- Kein API-Schlüssel erforderlich. Keine Garantie für Vollständigkeit oder Genauigkeit. Wichtige Termine beim Unternehmen bestätigen.
