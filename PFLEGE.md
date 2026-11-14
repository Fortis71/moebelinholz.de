# Pflege der Website moebelinholz.de

## Grundregel: Design-Schutz

- **Layout, Look, Farben, Typografie, Art und Größe der Bilder sowie das Bildformat bleiben wie erstellt.**
  Änderungen daran nur nach ausdrücklicher Genehmigung von Oliver Kranz (brand-neu-digital).
- **Inhaltliche Änderungen** (Texte, Bildunterschriften, neue Arbeiten, Kontaktdaten, Impressum, Datenschutz)
  dürfen sofort umgesetzt werden.

## Neue Arbeit hinzufügen

1. Bild als **WebP mit ca. 80 % Qualität**, längste Kante **max. 1600 px**, in `img/` ablegen.
   Dateiname klein, ohne Umlaute und Leerzeichen, z. B. `sideboard-eiche.webp`.
2. In `js/works.js` eine Zeile ergänzen:
   ```js
   ['sideboard-eiche','wohnen','Sideboard in Eiche mit Schubkästen'],
   ```
   Kategorien: `kueche`, `einbau`, `solitaer`, `buero`, `wohnen`.
3. Fertig: Die Arbeit erscheint auf `arbeiten.html` und wird auf der Startseite in die wechselnde Auswahl aufgenommen.

## Startseite: wechselnde Auswahl

Die 9 Startbilder stehen in `index.html` in der Liste `START` (Dateinamen ohne Endung).
Danach tauscht alle 3 Sekunden eine Kachel ihr Bild gegen eine andere Arbeit aus `js/works.js`.

## Hero-Slider

Die drei Motive (Venusschrank, Werkbank, Küche) stehen in `index.html` im Abschnitt `class="hero"`.
Texte dürfen angepasst werden; Aufbau und Gestaltung nicht ohne Genehmigung.

## Rechtliches

Impressum und Datenschutzerklärung stehen in `index.html` (Abschnitte `v-impressum` und `v-datenschutz`).
Stand der Datenschutzerklärung bei Änderungen aktualisieren.
