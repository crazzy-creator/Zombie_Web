# Texturen

Alle Dateien in diesem Ordner werden beim Start geladen. Du kannst jede Datei einzeln durch deine eigene ersetzen
(gleicher Dateiname, PNG). Fehlt eine Datei, nutzt das Spiel automatisch eine selbst erzeugte Ersatztextur.

| Datei | Größe | Zweck | Hinweise |
|---|---|---|---|
| `skin.png` | 256×256 | Haut (Zombie) | **kachelbar** (nahtlos in beide Richtungen), Wiederholung alle ~150 px |
| `flesh.png` | 256×256 | Fleisch/Muskel unter der Haut | kachelbar, Fasern waagerecht |
| `shirt.png` | 256×256 | Oberteil | **grau/hell** zeichnen: wird im Kleidershop mit der gewählten Farbe multipliziert. kachelbar |
| `pants.png` | 256×256 | Hose | grau/hell, wird eingefärbt, kachelbar |
| `shoe.png` | 256×256 | Schuhe | grau/hell, wird eingefärbt, kachelbar |
| `gut_small.png` | 128×64 | Dünndarm | Länge verläuft in **x-Richtung** (muss horizontal kacheln), y = Breite des Schlauchs (Mitte hell, Ränder dunkel) |
| `gut_colon.png` | 128×64 | Dickdarm | wie oben; alle 32 px eine Falte (Haustren) |
| `brain.png` | 256×256 | Gehirn | kachelbar, Furchen |
| `lung.png` | 256×256 | Lunge | kachelbar, rosa mit Äderchen |
| `heart.png` | 256×256 | Herz | kachelbar, dunkelrot |
| `liver.png` | 256×256 | Leber | kachelbar, braunrot glatt |
| `stomach.png` | 256×256 | Magen | kachelbar, rosa Falten |
| `metal.png` | 256×256 | Roboter-Außenhaut | kachelbar, Stahl mit Plattenfugen |
| `inner.png` | 256×256 | Roboter-Innenleben | kachelbar, dunkle Platine |

Tipps
- Kleidung (`shirt`, `pants`, `shoe`) bewusst **neutral grau** malen, sonst verfälscht die Einfärbung.
- Texturen werden mit Mipmaps gerendert: Zweierpotenzen (128/256/512) verwenden.
- Blut, Wundränder, Knochen und Organe sind aktuell Vektor-/Code-Grafik und noch nicht in diesem Ordner.
