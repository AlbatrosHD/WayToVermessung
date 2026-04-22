---
title: Koordinatensystem und Bezugssystem
topic: Koordinatensystem und Bezugssystem
description: Hier wird auf die Koordinatensystem und Bezugssystem innerhalb von Europa eingegangen
draft:
tags:
---
## Einführung
Das Ziel der Geodäsie ist es die Erde oder teile der Erdoberfläche zeichnerisch darzustellen.  Grundsätzlich wird versucht die in der Natur vorhandenen Objekte sowie die Oberfläche der Erde in ihrer Größe und Lage darzustellen.
Welches sich aber als schwierig erweist, da die Erde ein Kartoffel ist. Aus diesen gründen versucht man über Bezugssysteme die Abbildung von Objekten in einem Koordinatensystem möglich zu machen.

## Bezugssysteme
### Definition und Bestandteile

Ein Bezugssystem setzt sich aus folgenden Elementen zusammen:

1. **Koordinatensystem**:  
    Ein mathematisches System, das Punkte im Raum durch Koordinaten (z. B. x, y, z oder Breite, Länge, Höhe) beschreibt. Beispiele sind kartesische Koordinaten oder geographische Koordinaten.
    
2. **Referenzpunkt (Ursprung)**:  
    Ein festgelegter Punkt, von dem aus die Koordinaten gemessen werden. In der Geodäsie ist dies oft der Erdmittelpunkt oder ein definierter Punkt auf der Erdoberfläche.
    
4. **Zeitbezug (optional)**:  
    Bei dynamischen Systemen, wie der Satellitennavigation, wird zusätzlich ein Zeitbezug benötigt, um Bewegungen zu beschreiben.
    

### Grundlegende Formen von Bezugskörpern

In der Geodäsie und verwandten Wissenschaften werden verschiedene Bezugskörper verwendet, um Berechnungen mit optimaler Genauigkeit und Effizienz durchzuführen. Die Wahl des Bezugskörpers richtet sich dabei nach der Größe des zu vermessenden Gebiets und den Anforderungen an die Präzision:

- Ebene: für lokale Vermessungen in kleinen Gebieten (bis ca. 10 km)
- Kugel: für regionale Anwendungen in mittleren Gebieten (bis ca. 100 km)
- Ellipsoid: für großräumige Vermessungen in ausgedehnten Gebieten (> 100 km)

Diese gestufte Vorgehensweise ermöglicht es, den Berechnungsaufwand zu minimieren, ohne die erforderliche Genauigkeit zu beeinträchtigen.

Hier nochmal die wichtigsten Bezugskörper aufgelistet: 

1. **Kugel (Sphäre)**
	- **Beschreibung**: Eine Kugel ist die einfachste Annäherung an die Form der Erde. Sie wird durch einen konstanten Radius r definiert.
    - **Anwendung**: Wird oft in theoretischen Modellen oder für grobe Näherungen verwendet, da die Erde annähernd kugelförmig ist.
    - **Beispiel**: In der Astronomie oder für einfache Berechnungen der Erdkrümmung.

![[../../MediaFiles/Pasted image 20260415121431.png|300]]

2. **Ellipsoid**
    
    - **Beschreibung**: Ein Rotationsellipsoid ist ein mathematisches Modell, das die abgeplattete Form der Erde besser beschreibt als eine Kugel. Es wird durch eine große Halbachse a (Äquatorradius) und eine kleine Halbachse b (Polradius) definiert.
    - **Anwendung**: Wird in der Geodäsie als Referenzellipsoid verwendet, um präzise Koordinatensysteme zu definieren.
    - **Beispiel**: Das **WGS84-Ellipsoid** oder das **GRS80-Ellipsoid** sind Standardmodelle für globale Vermessungen.


![[../../MediaFiles/regional-0_orig.jpg|300]]

Quelle: https://www.tobymarthews.com/gisbasics.html


3. **Geoid**
    - **Beschreibung**: Das Geoid ist die Niveaufläche (Äquipotentialfläche) das von verschiedenen Einflüssen (z.B. Erdgezeiten, Luftdruckschwankungen) befreiten Erdschwerefeldes in höhe des mittleren Meeresspiegels.
    - **Anwendung**: Wird für präzise Höhenmessungen und als Referenzfläche für die Definition von Höhen über dem Meeresspiegel verwendet.
    - **Beispiel**: Das **EGM96** (Earth Gravitational Model 1996) beschreibt das Geoid global.


4. **Quasigeoid**
	- **Beschreibung**: Das Quasigeoid ist eine mathematisch definierte Fläche, die Normalhöhen referenziert. Es ermöglicht die Umrechnung von geometrischen Höhen (z. B. aus GNSS) in Normalhöhen und ist eine vereinfachte Alternative zum Geoid für praktische Anwendungen. 
	- **Anwendung**: Umrechnung von GNSS-gemessenen geometrischen Höhen in Normalhöhen für präzise Höhenangaben in modernen Höhenreferenzsystemen wie dem DHHN2016 oder EVRS

![[../../MediaFiles/Geoidheight_DE.svg.png|300]]

Quelle: https://de.wikipedia.org/wiki/Quasigeoid

5. **Zylinder**
    
    - **Beschreibung**: Ein Zylinder wird in lokalen Bezugssystemen oder für spezielle Anwendungen verwendet, z. B. in der Ingenieurvermessung.
    - **Anwendung**: Wird oft für die Projektion von Koordinaten in ebenen Systemen genutzt, wie beim **UTM-Koordinatensystem** (Universal Transverse Mercator).

![[../../MediaFiles/Pasted image 20260415130408.png|300]]

6. **Ebene**
    
    - **Beschreibung**: Eine Ebene wird für lokale Vermessungen oder in der Kartographie verwendet, um kleine Ausschnitte der Erdoberfläche ohne Krümmung darzustellen.
    - **Anwendung**: Wird in der Ingenieurgeodäsie für Bauprojekte oder in der Katastervermessung genutzt.



## Koordinatensysteme

### Geographische (Sphäre) Koordinaten
![[../../MediaFiles/20260415_132533810.jpg|300]]
- Schnittebenen durch Kugel ergeben Kreise
- Großkreis: durch Mittelpunkt
- Kleinkreis: nicht durch Mittelpunkt
- Äquator = einziger Breitenkreis als Großkreis
- Längenkreise schneiden sich in Nord- und Südpol
- Meridian = kürzeste Verbindung zwischen Polen

- geografische Breite: Winkel zur Äquatorebene
- geografische Länge: Winkel zum Nullmeridian (Greenwich)
Gitternetz entsteht durch Breiten- und Längenkreise
### Geodätische (Ellipsoid) Koordinaten
![[../../MediaFiles/20260415_132541385.jpg|300]]
- geodätische Breite: Winkel zwischen Ellipsoidnormalen und Äquatorebene
- geodätische Länge: Winkel zum Nullmeridian

### Gauß-Krüger Koordinaten
![[../../MediaFiles/IMG_20260415_133350446.jpg|300]]

![[../../MediaFiles/IMG_20260415_133913959.jpg|300]]

- transversale Mercator-Abbildung
- Meridianstreifen: 3°
- längentreu am Mittelmeridian
Koordinaten:
- Rechtswert (Y)
- Hochwert (X)
Mittelmeridian:
- Bezugsmeridian
- X-Achse
Koordinatenursprung:
- Schnittpunkt Äquator & Mittelmeridian
### Mercator Koordinaten
- Zylinderprojektion
- winkeltreu
- längentreu nur an Berührungslinien
Normale Mercator:
- Zylinderachse = Erdachse
Transversale Mercator:
- Zylinderachse senkrecht zur Erdachse

UTM = Universale Transversale Mercator-Projektion
- Bezugsellipsoid: GRS80
- Meridianstreifen: 6°
- 20 Breitenbänder
UTM-Koordinaten:
- rechtwinklige (kartesische) Koordinaten im Landesbezugssystem
- Quadranten werden im Uhrzeigersinn gezählt
- y-Achse zeigt nach Osten - Ostwert (East)
- Ostwert: 500.000 m ± Abstand
- x-Achse zeigt nach Norden - Nordwert (North)
- Nordwert: Abstand vom Äquator
längentreu an Durchdringungskreisen

![[../../MediaFiles/IMG_20260415_133930902.jpg|300]]