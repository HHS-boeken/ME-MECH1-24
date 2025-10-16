# Uitwerkingen

## Terugblik Opgave 1

`````{admonition} Antwoord
:class:  dropdown

De oplegreacties in punt $A$ zijn:
\begin{align*}
    A_x &= 0 \text{ kN} \\
    A_y &= 23 \text{ kN} \uparrow \\
\end{align*}


De oplegreacties in punt $B$ zijn:
\begin{align*}  
    B_y &= 52 \text{ kN} \uparrow
\end{align*}


````{admonition} Uitwerking
:class:  dropdown

Maak een VLS:

```{figure} ../figures/HC6_0vls.png
---
width: 70%
name: HC6_0vls
align: center
---
: Voorbeeld Opgave 2 - VLS
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
&= - R_{q_1} \cdot \left( \dfrac{1}{3} \cdot 6 \right)  - R_{q_2} \cdot (4+3) + B_y \cdot 10 - T_1     \\
&= - \left( \dfrac{1}{2} \cdot 10 \cdot 6 \right) \cdot \left( \dfrac{1}{3} \cdot 6 \right)  - \left( 7.5 \cdot 6 \right) \cdot 7 + B_y \cdot 10 - 25     \\
&= -180 - 315 + 10B_y - 25      \\
&= -520 + 10B_y      \\
-10B_y &= -520 \\
B_y &= \dfrac{-520}{-10} \\
B_y &= \text{ kN} \uparrow
\end{align}


Verticale krachtenevenwicht geeft:
\begin{align}
\uparrow_+  \Sigma{F_y} &= 0 \\
&= A_y - R_{q_1} - R_{q_2} + B_y  \\
&= A_y - \left( \dfrac{1}{2} \cdot 10 \cdot 6 \right) -  \left( 7.5 \cdot 6 \right) + 52 \\
&= A_y - 30 - 45 + 52  \\
&= A_y - 23 \\
A_y &= 23 \text{ kN} \uparrow
\end{align}


````
`````

<hr style="border:1px solid #9EA700">

## Voorbeeld Opgave 1

`````{admonition} Antwoord
:class:  dropdown

a)

De oplegreacties in punt A zijn:
\begin{align*}
    A_x = 0 \text{ kN} \\
    A_y &\approx 32.17 \text{ kN} \uparrow \\
\end{align*}


De oplegreacties in punt B zijn:
\begin{align*}
    B_y &\approx 54.08 \text{ kN} \uparrow \\
\end{align*}

b)

De indrukking van de veer is;
\begin{align}
    \delta_b &\approx 0.0832  \text{ m} = 83.2  \text{ mm}
\end{align}

c) 

De verplaatsing in punt $C$ is;
\begin{align}
    \delta_c &\approx 0.116 \text{ m} = 116.48 \text{ mm} 
\end{align}

````{admonition} Uitwerking
:class:  dropdown

a)

Maak een VLS:

```{figure} ../figures/HC6_1vls.png
---
width: 70%
name: HC6_1vls
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

a)

De oplegreacties in punt $A$ zijn:
\begin{align*}
    A_y &\approx 51.17 \text{ kN} \uparrow
\end{align*}

De oplegreacties in punt $B$ zijn:
\begin{align*}
    B_y &\approx 52.83 \text{ kN} \uparrow
\end{align*}

b)

Bereken de verplaatsing van de veer in punt $A$ is;
\begin{align}
    \delta_a &\approx 0.341  \text{ m}
\end{align}

Bereken de verplaatsing van de veer in punt $B$ is;
\begin{align}
   \delta_b &\approx 0.096  \text{ m}
\end{align}

c)

De verplaatsing in punt $C$ is;
\begin{align}
   \delta_c &\approx 0.06 \text{ m}
\end{align}

````{admonition} Uitwerking
:class:  dropdown

Maak een VLS:

```{figure} ../figures/HC6_2vls.png
---
width: 70%
name: HC6_1vls
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
B_y &\approx 52.83 \text{ kN} \uparrow 
\end{align}

Verticale krachtenevenwicht geeft:
\begin{align}
\uparrow_+  \Sigma{F_y} &= 0 \\
&= A_y -  (13\cdot 8) + B_y   \\
&= A_y - 104 + 52.83\\
&= A_y - 51.17  \\
A_y &\approx 51.17 \text{ kN} \uparrow
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

De stijfheid, $k$, van de veer is;
\begin{align}
    k &= 175.34 \text{ N/m} 
\end{align}


````{admonition} Uitwerking
:class:  dropdown

Maak een VLS:



Stel de evenwichtsvergelijkingen op:

Horizontale krachtenvevenwicht geeft:
\begin{align}
\rightarrow_+ \Sigma{F_x} &= 0 \\
&= - T_{CD} \cdot \dfrac{1}{\sqrt{2}} + T_{BD} \cdot \dfrac{3}{\sqrt{13}} \\
T_{CD} \cdot \dfrac{1}{\sqrt{2}} &=  T_{BD} \cdot \dfrac{3}{\sqrt{13}}
\end{align}

Verticale krachtenevenwicht geeft:
\begin{align}
\uparrow_+  \Sigma{F_y} &= 0 \\
&= T_{CD} \cdot \dfrac{1}{\sqrt{2}} + T_{BD} \cdot \dfrac{2}{\sqrt{13}} - 40 \cdot 9.81 \\
\end{align}

$T_{CD}$ invullen geeft;
\begin{align}
\uparrow_+  \Sigma{F_y} &= 0 \\
&= T_{CD} \cdot \dfrac{1}{\sqrt{2}} + T_{BD} \cdot \dfrac{2}{\sqrt{13}} - 40 \cdot 9.81 \\
&= T_{BD} \cdot \dfrac{3}{\sqrt{13}} + T_{BD} \cdot \dfrac{2}{\sqrt{13}} - 392.4 \\
&= T_{BD} \left( \dfrac{3}{\sqrt{13}} + \dfrac{2}{\sqrt{13}} \right) - 392.4 \\
&= 1.39T_{BD} - 392.4 \\
T_{BD} &\approx \dfrac{392.4}{1.39} \\
T_{BD} &\approx 282.30 \text{ N}
\end{align}

$T_{BD}$ invullen geeft;
\begin{align}
\rightarrow_+ \Sigma{F_x} &= 0 \\
T_{CD} \cdot \dfrac{1}{\sqrt{2}} &=  T_{BD} \cdot \dfrac{3}{\sqrt{13}} \\
T_{CD} \cdot \dfrac{1}{\sqrt{2}} &=  282.30 \cdot \dfrac{3}{\sqrt{13}} \\
T_{CD}  &=  332.18 \text{ N}
\end{align}

De uitgerekte lengte van de veer is;
\begin{align}
    l &= \sqrt{3^2 + 2^2} \\
    l &= \sqrt{13}
\end{align}

De verlenging, $x$ van de veer is;
\begin{align}
    x &= \sqrt{13} -2 \\
    x &\approx 1.61 \text{ m}
\end{align}

De stijfheid, $k$, van de veer is;
\begin{align}
    F &= k \cdot x \\
    k &= \dfrac{F}{x} \\
    &= \dfrac{282.30}{1.61} \\
    &= 175.34 \text{ N/m} 
\end{align}
````
`````

<hr style="border:1px solid #9EA700">

