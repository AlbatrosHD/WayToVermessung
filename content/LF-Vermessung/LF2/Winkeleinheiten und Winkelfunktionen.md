---
title: Winkeleinheiten und Winkelfunktionen
topic: Winkeleinheiten
description: Hier geht es um die verschiedenen Winkeleinheiten der Geodäsie und Mathematik
draft:
tags:
---
## Einleitung zu Winkeleinheiten

Die Geodäsie, als Wissenschaft von der Ausmessung und Abbildung der Erdoberfläche, basiert auf präzisen Winkelmessungen. Winkeleinheiten bilden dabei eine zentrale Grundlage für die Erfassung, Berechnung und Darstellung räumlicher Beziehungen. In diesem Kontext sind verschiedene Winkeleinheiten von Bedeutung, die je nach Anwendung und Genauigkeitsanforderung eingesetzt werden.

### Bedeutung der Winkeleinheiten in der Geodäsie

Winkeleinheiten ermöglichen die exakte Beschreibung von Richtungen, Neigungen und Positionen im Raum. Sie sind essenziell für die Durchführung von Vermessungsarbeiten, die Erstellung von Karten sowie die Navigation. In der Geodäsie werden vor allem die folgenden Winkeleinheiten verwendet:

- **Grad (°):** Die gebräuchlichste Einheit im Alltag und in vielen technischen Anwendungen. Ein Vollkreis umfasst 360 Grad. 
	- **Minuten ('):** Ein Grad besteht aus 60 Minuten. Bsp. $6'=0,1°*60 Minuten$
	- **Sekunden (''):** Eine Minute besteht aus 60 Sekunden. Bsp. $6''=0,1'*60 Sekunden$
	Diese Unterteilung ermöglicht eine besonders präzise Angabe von Winkeln, die in der Navigation und Astronomie von großer Bedeutung ist.
- **Gon (gon):** Auch als Neugrad bezeichnet, unterteilt den Vollkreis in 400 Gon. Diese Einheit wird insbesondere in der europäischen Vermessungstechnik bevorzugt, da sie eine dezimale Unterteilung ermöglicht und somit Berechnungen vereinfacht.
- **Radiant (rad):** Die natürliche Winkeleinheit in der Mathematik und Physik, die auf dem Verhältnis von Bogenlänge zum Radius eines Kreises basiert. Ein Vollkreis entspricht 2\pi Radiant.
- **Strich (‰):** Eine Einheit, die vor allem im militärischen Bereich verwendet wird. Ein Vollkreis umfasst 6400 Strich.
> [!info] Umrechnung
> $$\alpha°:0,9=\alpha_{gon} \ \ \ und \ \ \ \alpha_{gon}*0,9 =\alpha °$$ 
### Anwendungsbereiche und Relevanz

Die Wahl der Winkeleinheit hängt stark vom jeweiligen Anwendungsbereich ab. Während in der klassischen Landvermessung oft Gon verwendet werden, kommen in der Navigation und Astronomie häufig Grad zum Einsatz. Radiant werden vor allem in theoretischen Berechnungen und mathematischen Modellen genutzt. Die Umrechnung zwischen diesen Einheiten ist ein zentraler Aspekt der geodätischen Praxis, um Messergebnisse vergleichbar und nutzbar zu machen.

## Winkelfunktionen
Die #Winkelfunktionen, auch #trigonometrische-Funktionen genannt, bilden eine der grundlegenden Säulen der Mathematik und finden Anwendung in zahlreichen wissenschaftlichen und technischen Disziplinen, von der Physik über die Ingenieurwissenschaften bis hin zur Geodäsie. Ihre Definition und ihr Verständnis basieren maßgeblich auf dem Konzept des Einheitskreises, einem Kreis mit dem Radius r = 1 , der im kartesischen Koordinatensystem zentriert ist.

![[../../MediaFiles/Einheitskreis.webp]]

Quelle: https://beat-trachsler.ch/geogebra/trigo/

### Der Einheitskreis als Grundlage

Der Einheitskreis ist ein Kreis mit dem Radius 1, dessen Mittelpunkt im Ursprung (0, 0) eines Koordinatensystems liegt. Jeder Punkt auf dem Umfang des Einheitskreises kann durch einen Winkel $\theta$ beschrieben werden, der im mathematisch positiven Sinn (gegen den Uhrzeigersinn) von der positiven x-Achse aus gemessen wird. Die Koordinaten eines solchen Punktes P auf dem Einheitskreis sind direkt mit den Winkelfunktionen verknüpft:

|                    | Darstellung    | Funktionswert                                                                          |
| ------------------ | -------------- | -------------------------------------------------------------------------------------- |
| <h3>Kosinus</h3>   | ![[Bild.png]]  | <br>$cos(\alpha)=\frac{Ankathete}{Hypotenuse}$                                         |
| <h3>Sinus</h3>     | ![[Bild1.png]] | $sin(\alpha)=\frac{Gegenkathete}{Hypotenuse}$                                          |
| <h3>Tangens</h3>   | ![[Bild2.png]] | $tan(\alpha)=\frac{Gegenkathete}{Ankathete}$                                           |
| <h3>Kotangens</h3> | ![[Bild3.png]] | $cot(\alpha)=\frac{1}{tan\alpha}=\frac{Ankathete}{Gegenkathete}$                       |
| <h3>Kosekans</h3>  | ![[4.png]]     | $csc(\alpha)=\frac{1}{\sin{𝛼}}=\frac{𝐻𝑦𝑝𝑜𝑡h𝑒𝑛𝑢𝑠𝑒}{𝐺𝑒𝑔𝑒𝑛𝑘𝑎𝑡h𝑒𝑡𝑒}$ |
| <h3>Sekans</h3>    | ![[5.png]]     | $sec(\alpha)=\frac{1}{cos(\alpha)}=\frac{Hypotenuse}{Ankathete}$                       |

