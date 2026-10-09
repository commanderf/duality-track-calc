# Changelog

Versionierung: SemVer mit Kanal-Suffix (`-alpha`, `-beta`, `-rc`); der Kanal wird in der App angezeigt.
Die oberste Version hier muss der Konstante `APP_VERSION` in `duality-streifenrechner.html` entsprechen (prüft `check.js`).
Derselbe Changelog ist in der App unter „Änderungen" eingeblendet.

## [0.2.0-alpha] – 2026-10-09

### Hinzugefügt
- Wandplaner als zweiter Tab: Teile per Drag & Drop auf eine Wand, maßstäbliche Bänder (35,8 mm), Wandmaße und 50-mm-Raster
- Magnet-Snapping an freien Endpunkten (45°-Raster), `Shift` schaltet den Magnet ab
- Drehen (R/Shift+R), Spiegeln (F), Löschen (Entf), Rückgängig (Strg+Z), Zoom/Pan, Inspector, „Plan als Stückliste"
- Drehen im Inspector in beide Richtungen (+45° und −45°) – auch für Tablets ohne Tastatur
- Klonen des gewählten Teils: wird am freien Ende angesetzt und läuft tangential weiter (bei Geraden identische Ausrichtung; Knopf im Inspector oder Strg+D)
- Wandplan als PNG exportieren („Bild speichern", auf die Wand zugeschnitten)
- Wandplan in localStorage und JSON-Export/-Import; der Export markiert die App-Version

### Behoben
- Wandplaner-Tab zeigte die Streifenliste darüber (`hidden` wurde von `.grid{display:grid}` überstimmt)
- Ziehen aus der Palette war per Touch nicht möglich (fehlendes `touch-action:none`)

## [0.1.0] – 2026-10-08

### Hinzugefügt
- Erste Version: Streifenrechner aller 56 strip-führenden Teile mit Pfadlänge, Auswahl, Summe/Rollen-Rest, JSON-Export/-Import
