# AP1 Mechatroniker 2026 - Lars1909-crtl

Live: https://Lars1909-crtl.github.io/ap1-f26/

Diese App ist iPad Pro 5. Gen 12.9" optimiert, offline fähig, ohne Platzhalter.

## Inhalt
- `index.html` = fertige App (Lernplan 21 Tage OHNE Zeitangaben, OHNE Wochen-Einteilung, nur Tag/Thema/Können)
- `manifest.json` = PWA Manifest
- `icon-*.png` = Icons für Home-Bildschirm
- `mobileconfig/` = Profile für 2 Icons (optional)

## GitHub Pages Deployment (1 Minute)
1. Repo erstellen: `ap1-f26` Public
2. Diese ZIP entpacken und alle Dateien in Repo root hochladen (wichtig: index.html muss im Root liegen, nicht in Unterordner)
3. Settings -> Pages -> Source: Deploy from a branch -> Branch: main, Folder: / (root) -> Save
4. Warten bis Deployments grün (1-2 Min)
5. Live: https://Lars1909-crtl.github.io/ap1-f26/

## Installation auf iPad
WEG 1 (ohne Profil, empfohlen):
Safari -> https://Lars1909-crtl.github.io/ap1-f26/ -> Teilen-Icon -> Zum Home-Bildschirm -> Hinzufügen

WEG 2 (mit Profil, 2 Icons):
.mobileconfig aus Ordner mobileconfig/ per AirDrop/Mail ans iPad senden -> Einstellungen -> Allgemein -> VPN & Geräteverwaltung -> Installieren

## Verteilung an Azubis
In der App Tab "Teilen für Azubis" ist ein QR-Code der fix auf https://Lars1909-crtl.github.io/ap1-f26/ zeigt. Ausdrucken oder als Bild speichern.

## Kein Platzhalter mehr
Alle Links zeigen fix auf Lars1909-crtl.github.io/ap1-f26/ - kein sebastian-ibanez.github.io mehr.

## Offline
App speichert Lernfortschritt (21 Tage abhaken) im localStorage des Browsers - funktioniert auch ohne WLAN in der Werkstatt.
