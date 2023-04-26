# Aufgabe 1
### a)
Mit einem hex editor können wir sehen, dass die ersten beiden bytes
0x42 und 0x4d sind, das sagt uns dass die header im little endian
geschrieben wurden

### b)
```
Header Größe: 0x28 = 40
Bildbreite = 0x0A = 10
Bildhöhe = 0x0A = 10
Farbebenen = 0x01 = 1
Bits pro Pixel = 0x18 = 24
Kompressionsmethode = 0
Bildgröße = 0x42 01 = 322
Horizontale Auflößung = 0xC2 1E = 7874
Vertikale Auflößung = 0xC2 1E = 7874
Anzahl Farben der Palette = 0
Anzahl der wichigen Farben = 0
```

### c)

Breite und Höhe C1 = 0x0C 0x0C = 12

Breite und Höhe C2 = 0x0C 0xF4 FF FF FF = -12

Eine negative höhe könnte bedeuten dass die pixel das bild in umgekehrter
reihenfolge füllen.


