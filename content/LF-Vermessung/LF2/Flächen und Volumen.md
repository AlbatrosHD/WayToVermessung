## 2D Flächenberechnungen

## Quadrat
$$A = a^2$$
- $a$ = Seitenlänge

## Rechteck
$$A = l \cdot b$$
- $l$ = Länge, $b$ = Breite

## Dreieck (allgemein)
$$A = \frac{1}{2} \cdot b \cdot h$$
- $b$ = Basis, $h$ = Höhe

## Dreieck (nach Heron)
$$A = \sqrt{s(s-a)(s-b)(s-c)}, \quad s = \frac{a+b+c}{2}$$
- $a, b, c$ = Seitenlängen, $s$ = Halbumfang

## Gleichseitiges Dreieck
$$A = \frac{\sqrt{3}}{4} \cdot a^2$$
- $a$ = Seitenlänge

## Parallelogramm
$$A = b \cdot h$$
- $b$ = Basis, $h$ = senkrechte Höhe

## Raute (Rhombus)
$$A = \frac{d_1 \cdot d_2}{2}$$
- $d_1, d_2$ = Diagonalen

## Trapez
$$A = \frac{(a + c)}{2} \cdot h$$
- $a, c$ = parallele Seiten, $h$ = Höhe

## Kreis
$$A = \pi r^2$$
- $r$ = Radius

## Ellipse
$$A = \pi \cdot a \cdot b$$
- $a$ = große Halbachse, $b$ = kleine Halbachse

## Kreissektor
$$A = \frac{1}{2} r^2 \cdot \varphi$$
- $r$ = Radius, $\varphi$ = Mittelpunktswinkel in Radiant

> Umrechnung: $\varphi = \frac{\alpha \cdot \pi}{200^{gon}}$

## Kreissegment
$$A = \frac{r^2}{2}(\varphi - \sin\varphi)$$
- $r$ = Radius, $\varphi$ = Mittelpunktswinkel in Radiant

## Kreisring (Annulus)
$$A = \pi(R^2 - r^2)$$
- $R$ = äußerer Radius, $r$ = innerer Radius

## Regelmäßiges $n$-Eck
$$A = \frac{n \cdot a^2}{4} \cdot \cot\!\left(\frac{\pi}{n}\right)$$
- $n$ = Anzahl der Ecken, $a$ = Seitenlänge

## Regelmäßiges Sechseck
$$A = \frac{3\sqrt{3}}{2} \cdot a^2$$
- $a$ = Seitenlänge

## Regelmäßiges Fünfeck
$$A = \frac{a^2}{4}\sqrt{25 + 10\sqrt{5}}$$
- $a$ = Seitenlänge

## Drachen (Deltoid)
$$A = \frac{d_1 \cdot d_2}{2}$$
- $d_1, d_2$ = Diagonalen (wie Raute, aber ungleiche Seiten)

## Beliebiges Polygon (Gaußsche Trapezformel)
$$A = \frac{1}{2} \left| \sum_{i=0}^{n-1}(x_i \cdot y_{i+1} - x_{i+1} \cdot y_i) \right|$$
- $(x_i, y_i)$ = Eckpunkte des Polygons im Uhrzeigersinn


# Volumen- & Masseberechnung

## Grundformeln (Dichte / Masse / Volumen)

$$\rho = \frac{m}{V} \qquad m = \rho \cdot V \qquad V = \frac{m}{\rho}$$

| Größe   | Symbol | SI-Einheit         |
|---------|--------|--------------------|
| Masse   | $m$    | $\rm{kg}$          |
| Volumen | $V$    | $\rm{m^3}$         |
| Dichte  | $\rho$ | $\rm{kg \cdot m^{-3}}$ |

---

## Würfel
$$V = a^3$$
- $a$ = Kantenlänge

## Quader
$$V = l \cdot b \cdot h$$
- $l$ = Länge, $b$ = Breite, $h$ = Höhe

## Zylinder
$$V = \pi r^2 \cdot h$$
- $r$ = Radius der Grundfläche, $h$ = Höhe

## Kegel
$$V = \frac{1}{3} \pi r^2 \cdot h$$
- $r$ = Basisradius, $h$ = Höhe

## Pyramide (allgemein)
$$V = \frac{1}{3} \cdot A_G \cdot h$$
- $A_G$ = Grundfläche, $h$ = Höhe

## Pyramide (quadratische Basis)
$$V = \frac{1}{3} \cdot a^2 \cdot h$$
- $a$ = Seitenlänge der Basis, $h$ = Höhe

## Kugel
$$V = \frac{4}{3} \pi r^3$$
- $r$ = Radius

## Halbkugel
$$V = \frac{2}{3} \pi r^3$$
- $r$ = Radius

## Kugelschicht (Kugelabschnitt)
$$V = \frac{\pi h}{6}(3r_1^2 + 3r_2^2 + h^2)$$
- $h$ = Höhe der Schicht, $r_1, r_2$ = Radien der Schnittkreise

## Prisma (allgemein)
$$V = A_G \cdot h$$
- $A_G$ = Grundfläche (beliebiges Polygon), $h$ = Höhe

## Dreiseitiges Prisma (Triangularprisma)
$$V = \frac{1}{2} \cdot b \cdot h_\triangle \cdot l$$
- $b$ = Basis des Dreiecks, $h_\triangle$ = Höhe des Dreiecks, $l$ = Länge des Prismas

## Ellipsoid
$$V = \frac{4}{3} \pi \cdot a \cdot b \cdot c$$
- $a, b, c$ = Halbachsen

## Torus
$$V = 2\pi^2 \cdot R \cdot r^2$$
- $R$ = Abstand Mittelpunkt → Rohrmitte, $r$ = Rohrradius

## Kegelstumpf
$$V = \frac{\pi h}{3}(R^2 + R \cdot r + r^2)$$
- $R$ = großer Radius, $r$ = kleiner Radius, $h$ = Höhe

## Pyramidenstumpf
$$V = \frac{h}{3}(A_1 + A_2 + \sqrt{A_1 \cdot A_2})$$
- $A_1, A_2$ = Grundflächen (oben/unten), $h$ = Höhe

## Hohlzylinder (Rohr)
$$V = \pi (R^2 - r^2) \cdot h$$
- $R$ = äußerer Radius, $r$ = innerer Radius, $h$ = Höhe

## Paraboloid
$$V = \frac{1}{2} \pi r^2 \cdot h$$
- $r$ = Basisradius, $h$ = Höhe

---

## Masse aus Volumen

$$\boxed{m = \rho \cdot V}$$

> **Beispiel:** Eisenkugel mit $r = 5\,\rm{cm}$, $\rho_{\rm{Fe}} = 7874\,\rm{kg/m^3}$
>
> $$V = \frac{4}{3}\pi (0{,}05)^3 \approx 5{,}236 \times 10^{-4}\,\rm{m^3}$$
>
> $$m = 7874 \cdot 5{,}236 \times 10^{-4} \approx 4{,}13\,\rm{kg}$$


# 🔺 Dreieck – Vollständige Formelsammlung

## Grundgrößen

- Seiten: $a, b, c$
- Gegenüberliegende Winkel: $\alpha, \beta, \gamma$
- Höhen: $h_a, h_b, h_c$
- Halbumfang: $s = \dfrac{a + b + c}{2}$

---

## Winkelsumme
$$\alpha + \beta + \gamma = 180°=200^{gon}$$

## Dreiecksungleichung
$$a < b + c \qquad b < a + c \qquad c < a + b$$

---

## Flächeninhalt

### Basis × Höhe (allgemein)
$$A = \frac{1}{2} \cdot a \cdot h_a = \frac{1}{2} \cdot b \cdot h_b = \frac{1}{2} \cdot c \cdot h_c$$

### Heronsche Formel (nur Seitenlängen bekannt)
$$A = \sqrt{s(s-a)(s-b)(s-c)}, \quad s = \frac{a+b+c}{2}$$

### Zwei Seiten + eingeschlossener Winkel
$$A = \frac{1}{2} \cdot a \cdot b \cdot \sin\gamma = \frac{1}{2} \cdot b \cdot c \cdot \sin\alpha = \frac{1}{2} \cdot a \cdot c \cdot \sin\beta$$

### Gleichseitiges Dreieck
$$A = \frac{\sqrt{3}}{4} \cdot a^2$$

### Rechtwinkliges Dreieck (Katheten $a$, $b$)
$$A = \frac{1}{2} \cdot a \cdot b$$

---

## Umfang
$$U = a + b + c$$

---

## Höhen
$$h_a = \frac{2A}{a} \qquad h_b = \frac{2A}{b} \qquad h_c = \frac{2A}{c}$$

### Höhe im gleichseitigen Dreieck
$$h = \frac{\sqrt{3}}{2} \cdot a$$

### Höhe im rechtwinkligen Dreieck auf die Hypotenuse
$$h_c = \frac{a \cdot b}{c}$$

---

## Satz des Pythagoras (rechtwinkliges Dreieck)
$$c^2 = a^2 + b^2 \qquad \Rightarrow \quad c = \sqrt{a^2 + b^2}$$

### Kathetensatz
$$a^2 = c \cdot p \qquad b^2 = c \cdot q$$
- $p, q$ = Abschnitte der Hypotenuse durch die Höhe $h_c$

### Höhensatz
$$h_c^2 = p \cdot q$$

---

## Sinussatz
$$\frac{a}{\sin\alpha} = \frac{b}{\sin\beta} = \frac{c}{\sin\gamma} = 2R$$
- $R$ = Umkreisradius

## Kosinussatz
$$a^2 = b^2 + c^2 - 2bc\cos\alpha$$
$$b^2 = a^2 + c^2 - 2ac\cos\beta$$
$$c^2 = a^2 + b^2 - 2ab\cos\gamma$$

### Umgestellt nach Winkel
$$\cos\alpha = \frac{b^2 + c^2 - a^2}{2bc}$$

## Tangenssatz
$$\frac{a - b}{a + b} = \frac{\tan\!\left(\frac{\alpha - \beta}{2}\right)}{\tan\!\left(\frac{\alpha + \beta}{2}\right)}$$

---

## Inkreis

$$r = \frac{A}{s} = \frac{A}{\frac{a+b+c}{2}}$$

- $r$ = Inkreisradius, $s$ = Halbumfang

### Inkreisradius (rechtwinkliges Dreieck)
$$r = \frac{a + b - c}{2}$$

## Umkreis
$$R = \frac{a \cdot b \cdot c}{4A}$$

### Umkreisradius (rechtwinkliges Dreieck)
$$R = \frac{c}{2}$$
> Die Hypotenuse ist Durchmesser des Umkreises.

---

## Schwerpunkt (Centroid)
$$S = \left(\frac{x_1 + x_2 + x_3}{3},\ \frac{y_1 + y_2 + y_3}{3}\right)$$

## Seitenhalbierende (Median)
$$m_a = \frac{1}{2}\sqrt{2b^2 + 2c^2 - a^2}$$
$$m_b = \frac{1}{2}\sqrt{2a^2 + 2c^2 - b^2}$$
$$m_c = \frac{1}{2}\sqrt{2a^2 + 2b^2 - c^2}$$

---

## Winkelberechnung mit Trigonometrie (rechtwinklig)

$$\sin\alpha = \frac{\text{Gegenkathete}}{\text{Hypotenuse}} = \frac{a}{c}$$
$$\cos\alpha = \frac{\text{Ankathete}}{\text{Hypotenuse}} = \frac{b}{c}$$
$$\tan\alpha = \frac{\text{Gegenkathete}}{\text{Ankathete}} = \frac{a}{b}$$

---

## Dreiecksarten – Kurzübersicht

| Typ | Bedingung | Besonderheit |
|---|---|---|
| Rechtwinklig | $\gamma = 90°$ | $c^2 = a^2 + b^2$ |
| Gleichseitig | $a = b = c$ | $\alpha = \beta = \gamma = 60°$ |
| Gleichschenklig | $a = b$ | $\alpha = \beta$ |
| Spitzwinklig | Alle $< 90°$ | Umkreismittelpunkt innen |
| Stumpfwinklig | Ein $> 90°$ | Umkreismittelpunkt außen |