![[III._1.4_Polygonpunktber_Formular.pdf]]
## Rechenablauf
Gang einer Berechnung für einen offenen Polygonzug mit beidseitigen Koordinaten und Richtungsanschluss.

- Berechnung des An- und Abschlussrichtungswinkel ($t_{F1, A}$ und $t_{E, F2}$ )
	- $Rec \rightarrow Pol = t_i, S_i$  |  $t_i=arctan(\frac{\Delta Y}{\Delta X})$ | $\phi_i=arctan(\frac{\Delta X}{\Delta Y})$ 
	- Probe: $t_i + \phi_i = 100gon \ oder \ 500gon$

- Ermittlung des Winkelabschlussfehlers ($W=f_{\beta}$)
	- $W=t_E^{F2}+n*200gon-(t_{F1}^A+[\beta])$
	- $[\beta] \rightarrow$ Summe der Betas, $n \rightarrow$ Anzahl der Punkte

- Berechnung der Verbesserung ($V_{\beta}$) für den Berechnungs- bzw. Außenwinkel ($\beta$)
	- $V_{\beta}=\frac{W}{n}$

- Verbesserungen an die Berechnungswinkel anbringen (s. Formular)
	- $\beta_i = \beta_i'+ V_{\beta}$

- Berechnung der Richtungswinkel $P_1 - P_E$ ($t_{A,1};t_{1,n};t_{n, n+1}$)
	- $t_{i+1}=t_i \pm 200gon + \beta_i$ ggf. $\pm 400gon$

- Berechnung der vorläufigen Koordinatenunterschiede ($\Delta y' , \Delta x'$)
	- $Pol \rightarrow Rec (\Delta y', \Delta x') \rightarrow \begin{array}{c} \Delta y' = sin(t_i)*S \\ \Delta x' = cos(t_i)*S \end{array}$ 
	- Probe: $\Delta x' + \Delta y' = \sqrt{2*S*sin(t+50gon)}$

- Berechnung des Koordinatenanschlussfehlers ($f_x, f_y$)
	- $f_y=(Y_E-Y_A)-[\Delta y']$ und $f_x=(X_E-X_A)-[\Delta x']$
	- $f_s=\sqrt{f_y^2+f_x^2}$

- Berechnung des Koordinatenabschlussfehlers ($V\Delta y, V\Delta x$)
	- $V_{\Delta yi}=\frac{f_y}{[S]}*S_i$ und $V_{\Delta xi}=\frac{f_x}{[S]}*S_i$

- Berechnung der endgültigen Koordinaten (Y;X) (s. Formular)
	- $y_i=y_{i-1}+\Delta y_i ' + V_{\Delta yi}$ und $x_i=x_{i-1}+\Delta x_i' + V_{\Delta xi}$

- Ermittlung des Längs- und Querfehlers (L;Q) zur Genauigkeitsabschätzung
	- $L=S_{A,E}' * \frac{f_y *[\Delta y']+f_x * [\Delta x']}{[\Delta x']^2+[\Delta y']^2}$ und $Q=S_{A,E}' * \frac{f_y *[\Delta x']-f_x * [\Delta y']}{[\Delta x']^2+[\Delta y']^2}$ 

Beispiel: 
![[III._1.2_Polygonzug_Aufgabe_1.pdf]]

Beispiel:

1. Berechnung des An- und Abschlussrichtungswinkel
	- $t_{F1, A}=arctan(\frac{10380,33-10134,11}{16440,27-16360,27})=80,00040gon$ $t_{E, F2}=arctan(\frac{11146,45-11183,210}{16154,25-16086,25})=84,99998$  
2. Ermittlung des Winkelabschlussfehlers
	- $W=84,99998+4*200gon-(80,00040+804,98)=0,01958gon$ 

3. Berechnung der Verbesserung ($V_{\beta}$) für den Berechnungs- bzw. Außenwinkel ($\beta$)
	- $V_{\beta}=\frac{0,01958gon}{4}=0,00489gon$

4. Verbesserungen an die Berechnungswinkel anbringen und Berechnung der Richtungswinkel $P_1 - P_E$ 
	- $t_i =t_{i-1} \pm 200gon + \beta_i'+ V_{\beta}$ ggf. $\pm 400gon$ 
	- $t_{A,1}=80,00040gon + 200gon + (189,9950gon + 0,00489gon) - 400gon=70,0003 gon$
	- $t_{1,2}=70,0003gon + 200gon + (252,9950gon + 0,00489gon)-400gon=123,0002gon$
	- $t_{2,E}=123,0002gon + 200gon + (235,9950gon + 0,00489gon)-400gon=159,0001gon$
5. Berechnung der vorläufigen Koordinatenunterschiede
	- $\begin{array}{c} \Delta y' = sin(70,0003)*240m=213,84m \\ \Delta x' = cos(70,0003)*240m=108,96m \end{array}$ 
	- $\begin{array}{c} \Delta y' = sin(123,0002gon)*360m=336,76m \\ \Delta x' = cos(123,0002gon)*360m=-127,25m \end{array}$
	- $\begin{array}{c} \Delta y' = sin(159,0001gon)*420m=252,18m \\ \Delta x' = cos(159,0001gon)*420m=-335,87m \end{array}$

6. Berechnung des Koordinatenanschlussfehlers
	- $f_y=802,88-802,78=0,10m$ $f_x=-354,02-(-354,16)=0,14m$
	- $f_s=\sqrt{0,10m^2+0,14m^2}=0,18m$ 

7. Berechnung des Koordinatenabschlussfehlers
	- $V_{\Delta yi}=\frac{0,10m}{1020m}*240m=0,024m$ und $V_{\Delta xi}=\frac{0,14}{1020m}*240m=0,034m$
	- $V_{\Delta yi}=\frac{0,10m}{1020m}*360m=0,036m$ und $V_{\Delta xi}=\frac{0,14}{1020m}*360m=0,051m$
	- $V_{\Delta yi}=\frac{0,10m}{1020m}*420m=0,042$ und $V_{\Delta xi}=\frac{0,14}{1020m}*420m=0,059m$

8. Berechnung der endgültigen Koordinaten
	- $y_i=y_{i-1}+\Delta y_i ' + V_{\Delta yi}$ und $x_i=x_{i-1}+\Delta x_i' + V_{\Delta xi}$

![[Aufgabe1.pdf]]