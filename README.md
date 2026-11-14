# moebelinholz.de

Website der Werkstatt **Möbel in Holz** – Manfred Wölk, Ottersberg.
Design und Umsetzung: brand-neu-digital, Oliver Kranz (www.brand-neu.de).

Statische Website ohne CMS und ohne Build-Schritt: reines HTML, CSS und JavaScript.
Gehostet auf dem netcup-Server (Plesk), Dokumentenstamm `httpdocs`.

## Aufbau

| Pfad | Inhalt |
| --- | --- |
| `index.html` | Startseite (Slider, Leistungen, Projekt, wechselnde Auswahl, Über mich, Kontakt) inkl. Impressum (`#impressum`) und Datenschutz (`#datenschutz`) |
| `arbeiten.html` | Unterseite „Ausgewählte Arbeiten“ mit Filter und Großansicht |
| `js/works.js` | **Liste aller Arbeiten** (Bilddatei, Kategorie, Bildunterschrift) – gilt für beide Seiten |
| `css/style.css` | Gestaltung |
| `img/` | Bilder als WebP (80 % Qualität, max. 1600 px lange Kante), Logos als SVG |
| `fonts/` | Schriften lokal (Jost, Instrument Sans, Fraunces) – keine Google-Fonts-Verbindung |
| `logo/` | Logo-Dateien (positiv, negativ, negativ mit Grund) |

## Pflege

Siehe [PFLEGE.md](PFLEGE.md).

## Veröffentlichen

Geänderte Dateien in Plesk unter moebelinholz.de → Dateimanager → `httpdocs` hochladen
(oder Plesk-Git mit diesem Repository verbinden).
