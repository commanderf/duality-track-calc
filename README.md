# Duality LED Track Calculator

A single-file, dependency-free web app to calculate LED strip lengths and
plan walls for the **Duality LED Track System**.

Open `index.html` in any modern browser – no install, no server, no build
step. All work is stored locally in your browser (localStorage), with JSON
export/import for backup.

## Features

- **Strip list** – all 56 strip-carrying track parts with their path length
  in mm, a selectable quantity, the total length and the remainder against a
  spool length (default 5 m).
- **Wall planner** – place parts to scale (35.8 mm wide bands) on a wall:
  drag & drop, 45° rotation, mirroring and magnetic snapping at free ends.
  Clone a part so it continues the run tangentially, undo/redo, zoom/pan,
  wall dimensions and grid, and export the plan as a **PNG image**.
- **Bill of materials** – turn the wall plan into the quantity table with one
  click.
- **JSON export/import** – save or restore the whole configuration.
- **Bilingual UI** – switch the interface between German and English at any
  time.

## Usage

- **Online:** `https://xaas86.github.io/duality-track-calc/`.
- **Offline:** download `index.html` and open it directly in a browser.

## Notes and disclaimer

- Lengths are derived from the nominal dimensions in the part file names; for
  curved parts the values are rounded values based on the given radius and
  angle. Values may deviate slightly – please verify before ordering material.
- The wall planner draws a schematic center line of each track part.
- Not affiliated with the designer of the track system – see below.

## Credits

The **Duality Track System Bundle – Original Track and Evolution Pack** is a
design by **Andy Huot Creations**
(<https://www.printables.com/@AndyHuot_3193751>). The bundle covers all
tracks (Original and Evo); the tracks are also available as separate
projects:

- Bundle – Original Track and Evolution Pack:
  <https://www.printables.com/model/1637420-duality-track-system-bundle-original-track-and-evo>
- Track System (Original):
  <https://www.printables.com/model/1365700-duality-led-track-system>
- Evolution Pack:
  <https://www.printables.com/model/1637201-duality-evolution-pack>
- Skins (Creative Commons):
  <https://www.printables.com/model/1365694-creative-commons-duality-led-track-system-skins>

## License

Licensed under **Creative Commons Attribution-NonCommercial 4.0
International (CC BY-NC 4.0)** – free to use, share and adapt for
non-commercial purposes with attribution. Commercial use is not permitted.
See [`LICENSE`](LICENSE).

---

# Duality LED Track Calculator (Deutsch)

Eine einzige, abhängigkeitsfreie HTML-Datei zum Berechnen von
LED-Streifenlängen und zum Planen von Wänden für das **Duality LED Track
System**.

`index.html` in einem modernen Browser öffnen – keine Installation, kein
Server, kein Build. Alle Daten bleiben lokal im Browser (localStorage),
Sichern/Wiederherstellen per JSON-Export/-Import.

## Funktionen

- **Streifenliste** – alle 56 streifenführenden Track-Teile mit Pfadlänge in
  mm, wählbarer Menge, Gesamtlänge und Rest gegenüber einer Rollenlänge
  (Standard 5 m).
- **Wandplaner** – Teile maßstäblich (35,8 mm breite Bänder) auf eine Wand
  legen: Drag & Drop, 45°-Drehung, Spiegeln und Magnet-Snapping an freien
  Enden. Klonen setzt ein Teil tangential fort, Rückgängig/Wiederholen,
  Zoom/Pan, Wandmaße und Raster, Export des Plans als **PNG-Bild**.
- **Stückliste** – den Wandplan mit einem Klick in die Mengentabelle
  übernehmen.
- **JSON-Export/-Import** – die gesamte Konfiguration sichern/wiederherstellen.
- **Zweisprachige Oberfläche** – die Bedienoberfläche jederzeit zwischen
  Deutsch und English umschalten.

## Nutzung

- **Online:** `https://xaas86.github.io/duality-track-calc/`.
- **Offline:** `index.html` herunterladen und direkt im Browser öffnen.

## Hinweise und Haftung

- Die Längen werden aus den Nennmaßen der Dateinamen abgeleitet; bei
  gebogenen Teilen handelt es sich um Rundungswerte anhand von Radius und
  Winkel. Die Werte können geringfügig abweichen – bitte vor der
  Materialbestellung prüfen.
- Der Wandplaner zeichnet eine schematische Mittellinie je Track-Teil.
- Kein Zusammenhang mit dem Designer des Systems – siehe unten.

## Danksagung / Credits

Das **Duality Track System Bundle – Original Track and Evolution Pack** ist
ein Design von **Andy Huot Creations**
(<https://www.printables.com/@AndyHuot_3193751>). Das Bundle umfasst alle
Tracks (Original und Evo); die Tracks gibt es auch als einzelne Projekte:

- Bundle – Original Track and Evolution Pack:
  <https://www.printables.com/model/1637420-duality-track-system-bundle-original-track-and-evo>
- Track System (Original):
  <https://www.printables.com/model/1365700-duality-led-track-system>
- Evolution Pack:
  <https://www.printables.com/model/1637201-duality-evolution-pack>
- Skins (Creative Commons):
  <https://www.printables.com/model/1365694-creative-commons-duality-led-track-system-skins>

## Lizenz

Lizenziert unter **Creative Commons Namensnennung – Nicht kommerziell 4.0
International (CC BY-NC 4.0)** – kostenlose Nutzung, Weitergabe und
Bearbeitung für nicht-kommerzielle Zwecke mit Namensnennung. Kommerzielle
Nutzung ist nicht gestattet. Siehe [`LICENSE`](LICENSE).
