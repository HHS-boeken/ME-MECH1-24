# Uitwerkingen

## Voorbeeld Opgave 1

`````{admonition} Antwoord
:class:  dropdown

De oplegreacties in punt A zijn:
\begin{align*}
A_y &\approx 71.39 \text{ kN} \uparrow \\
\end{align*}


De oplegreacties in punt B zijn:
\begin{align*}
B_x &= 0 \text{ kN}\\
B_y &= \dfrac{-32.5}{-9} \approx 3.61 \text{ kN} \uparrow \\
\end{align*}

````{admonition} Uitwerking
:class:  dropdown

a)

Maak een VLS:

```{figure} ../figures/HC5_1vls.png
---
width: 70%
name: HC5_1vls
align: center
---
: Voorbeeld Opgave 1 - VLS
```

Stel de evenwichtsvergelijkingen op:

Horizontale krachtenvevenwicht geeft:
\begin{align}
\rightarrow_+ \Sigma{F_x} &= 0 \\
&= A_x = 0 \text{ kN}
\end{align}


Momentenevenwicht geeft:
\begin{align}
\circlearrowleft_+ \Sigma{M_{|A}}  &= 0 \\
&= -q_1 \cdot \left( \dfrac{2}{3} \cdot 5 \right) - F_1 \cdot 7 - T_1 + B_{y;veer} \cdot 10\\
&= - \left( \dfrac{1}{2} \cdot 5 \cdot 8.5 \right) \cdot \left( \dfrac{2}{3} \cdot 5 \right) - 65 \cdot 7 - T_1 + B_{y;veer} \cdot 10\\
&= -70.83 - 455 - 15 + 10B_{y;veer}
&= -540.83 + 10B_{y;veer} \\
-10B_y &= -540.83 \\
B_y &= \dfrac{-540.83}{-10} \approx 54.083 \text{ kN} \uparrow \\
\end{align}


Verticale krachtenevenwicht geeft:
\begin{align}
\uparrow_+  \Sigma{F_y} &= 0 \\
&= A_y - R_{q_1} - F_1 + B_{y;veer} \\
&= A_y - \left( \dfrac{1}{2} \cdot 5 \cdot 8.5 \right) - 65 + 54.08 \\
&= A_y - 21.25 -65 + 54.08\\
&= A_y - 32.17 \\
A_y &\approx 32.17 \text{ kN} \uparrow \\
\end{align}

b) 

Bereken de indrukking van de veer
\begin{align}
F &= k \cdot \delta_b \\
\delta_b &=  \dfrac{F}{k} \\
&= \dfrac{54.08}{650} \\
&\approx 0.0832  \text{ m} = 83.2  \text{ mm}
\end{align}

c)

Bereken de verplaatsing in punt $C$;

Gebruik verhoudigen van driehoeken;
\begin{align}
\dfrac{10}{0.0832} &= \dfrac{14}{\delta_c} \\
10\delta_c &= 0.0832 \cdot 14 \\
\delta_c &\approx \dfrac{14}{10} \cdot 0.0832 \\
&\approx 0.116 \text{ m} = 116.48 \text{ mm} 
\end{align}


````
`````

<hr style="border:1px solid #9EA700">

## Voorbeeld Opgave 2

`````{admonition} Antwoord
:class:  dropdown

De oplegreacties in punt A zijn:
\begin{align*}
A_x &= 0 \text{ kN} \\
A_y &= 72.5 \text{ kN} \uparrow \\
M_A &= 679.17  \text{ kNm} \circlearrowleft
\end{align*}


````{admonition} Uitwerking
:class:  dropdown

Maak een VLS:

```{figure} ../figures/HC5_2vls.png
---
width: 70%
name: HC5_1vls
align: center
---
: Voorbeeld Opgave 2 - VLS
```

Stel de evenwichtsvergelijkingen op:

Horizontale krachtenvevenwicht geeft:
\begin{align}
\rightarrow_+ \Sigma{F_x} &= 0 \\
&= 0 \text{ kN}
\end{align}

Momentenevenwicht geeft:
\begin{align}
\circlearrowleft_+ \Sigma{M_{|A}}  &= 0 \\
&=  - R_{q_1} \cdot (2+4) + B_y \cdot 12 - T_1 \\
&=  - (13 \cdot 8) \cdot (2+4) + B_y \cdot 12 - 10 \\
&= -624 + 12B_y -10 \\
&= -623 + 12B_y \\
-12B_y &= -623 \\
B_y &= \dfrac{-623}{-12} \\
B_y &= 52.83 \text{ kN} \uparrow 
\end{align}

Verticale krachtenevenwicht geeft:
\begin{align}
\uparrow_+  \Sigma{F_y} &= 0 \\
&= A_y -  (13\cdot 8) + B_y   \\
&= A_y - 104 + 52.83\\
&= A_y - 51.17  \\
A_y &= 51.17 \text{ kN} \uparrow
\end{align}

b)

Bereken de verplaatsing van de veer in punt $A$ en punt $B$

Punt $A$ geeft;
\begin{align}
F_1 &= k_1 \cdot \delta_A \\
\delta_A &=  \dfrac{F_1}{k_1} \\
\delta_A &=  \dfrac{A_y}{k_1} \\
&= \dfrac{51.17}{150} \\
&\approx 0.341  \text{ m}
\end{align}

Punt $B$ geeft;
\begin{align}
F_2 &= k_2 \cdot \delta_B \\
\delta_B &=  \dfrac{F_2}{k_2} \\
\delta_B &=  \dfrac{B_y}{k_2} \\
&= \dfrac{52.83}{550} \\
&\approx 0.096  \text{ m}
\end{align}

c)

Bereken de verplaatsing in punt $C$.

Stel een lineaire formule van de verplaastsing op;
\begin{align}
\delta(x) &= -0.341 + \dfrac{\Delta y}{\Delta x} x \\
&= -0.341 + \dfrac{0.341 - 0.096}{12} x
\end{align}

Dus in punt $C$ op $x=14$ geldt;
\begin{align}
\delta(14) &= -0.341 + \dfrac{0.341 - 0.096}{12} \cdot 14 \\
&= 0.06 \text{ m}
\end{align}
````
`````

<hr style="border:1px solid #9EA700">


## Voorbeeld Opgave 3

`````{admonition} Antwoord
:class:  dropdown

De oplegreacties in punt A zijn:
\begin{align*}
A_x &= -77.78 \text{ kN} = 77.78 \text{ kN} \leftarrow \\
M_A &= -78.86  \text{ kNm} = 78.86  \text{ kNm} \circlearrowright
\end{align*}


De oplegreacties in punt B zijn:
\begin{align*}
B_y &= -17.78 \text{ kN} = 17.78 \text{ kN} \downarrow
\end{align*}

````{admonition} Uitwerking
:class:  dropdown

Maak een VLS:

```{figure} ../figures/HC5_3vls.png
---
width: 70%
name: HC5_3vls
align: center
---
: Voorbeeld Opgave 3 - VLS
```

Stel de evenwichtsvergelijkingen op:

Horizontale krachtenvevenwicht geeft:
\begin{align}
\rightarrow_+ \Sigma{F_x} &= 0 \\
&= A_x + F_{1;x} \\
&= A_x + 110 \cdot \cos(45) \\
&= A_x + 77.78 \\
A_x &= -77.78 \text{ kN} = 77.78 \text{ kN} \leftarrow
\end{align}

Verticale krachtenevenwicht geeft:
\begin{align}
\uparrow_+  \Sigma{F_y} &= 0 \\
&= - (q_1 \cdot 5) - \left( \dfrac{1}{2} \cdot q_2 \cdot 5 \right) + F_{1;y} + B_y\\
&= - (q_1 \cdot 5) - \left( \dfrac{1}{2} \cdot q_2 \cdot 5 \right) + F \cdot \sin(45) + B_y\\
&= - (5 \cdot 6) - \left( \dfrac{1}{2} \cdot 10 \cdot 6 \right) + 110 \cdot \sin(45) + B_y\\
&= -30 - 30 + 77.78 + By \\
&= 17.78  + B_y \\
B_y &= -17.78 \text{ kN} = 17.78 \text{ kN} \downarrow
\end{align}

Momentenevenwicht geeft:
\begin{align}
\circlearrowleft_+ \Sigma{M_{|A}}  &= 0 \\
&= M_A - R_{q_1} \cdot 4 - R_{q_2} \cdot (1 + \dfrac{2}{3} \cdot 6 ) + F_{1;y} \cdot 9 - F_{1;x} \cdot 2 + B_y \cdot 11 \\
&= M_A - R_{q_1} \cdot 4 - R_{q_2} \cdot (1 + \dfrac{2}{3} \cdot 6 ) + F_1 \cdot \sin(45) \cdot 9 - F_1 \cdot \cos(45) \cdot 2 + B_y \cdot 11  \\
&= M_A - 30 \cdot 4 - 30 \cdot (1 + \dfrac{2}{3} \cdot 6 ) + 110 \cdot \sin(45) \cdot 9 - 110 \cdot \cos(45) \cdot 2 - 17.78 \cdot 11 \\
&= M_A - 120 - 150 + 700 - 155.56  - 195.58\\
&= M_A + 78.86\\
M_A &= -78.86  \text{ kNm} = 78.86  \text{ kNm} \circlearrowright
\end{align}

````
`````

<hr style="border:1px solid #9EA700">

