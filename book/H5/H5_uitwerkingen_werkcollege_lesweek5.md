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
&= A_x + R_{q2}
&= A_x + \dfrac{1}{2} \cdot 6 \cdot 10
&= A_x + 30
A_x &= -30 \text{ kN} = 30 \text{ kN} \leftarrow
\end{align}

Verticale krachtenevenwicht geeft:
\begin{align}
\uparrow_+  \Sigma{F_y} &= 0 \\
&= A_y - R_{q1} \\
&= A_y - \dfrac{1}{2} \cdot 6 \cdot 5 \\
&= A_y - 15 \\
A_y &\approx 15 \text{ kN} \uparrow \\
\end{align}

Momentenevenwicht geeft:
\begin{align}
\circlearrowleft_+ \Sigma{M_{|A}}  &= 0 \\
&= M_A - R_{q1} \cdot 3 - R{\cdot 1.5 - F_1 \cdot 3 - T + B_y \cdot 9\\
&= 15 \cdot 3 \cdot 1.5 - 30 \cdot 3 - 10 + B_y \cdot 9\\
&= 67.5 - 90 - 10 + 9B_y \\
-9B_y &= -32.5 \\
B_y &= \dfrac{-32.5}{-9} \approx 3.61 \text{ kN} \uparrow \\
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
&= A_x = 0 \text{ kN}
\end{align}

Verticale krachtenevenwicht geeft:
\begin{align}
\uparrow_+  \Sigma{F_y} &= 0 \\
&= A_y - \left( \dfrac{1}{2} \cdot q_1 \cdot 5 \right) - F_1  \\
&= A_y - \left( \dfrac{1}{2} \cdot 5 \cdot 5 \right) - 60 \\
&= A_y - 12.5 - 60  \\
&= A_y - 72.5 \\
A_y &= 72.5 \text{ kN} \uparrow
\end{align}

Momentenevenwicht geeft:
\begin{align}
\circlearrowleft_+ \Sigma{M_{|A}}  &= 0 \\
&= M_A - R_{q_1} \cdot \left( 3+ \dfrac{2}{3} \cdot 5 \right)  - F_1 \cdot 10   \\
&= M_A - 12.5 \cdot \left( 3+ \dfrac{2}{3} \cdot 5 \right)  - 60 \cdot 10   \\
&= M_A - 79.17 - 600 \\
&= M_A - 679.17 \\
M_A &= 679.17  \text{ kNm} \circlearrowleft
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


## Voorbeeld Opgave 4

`````{admonition} Antwoord
:class:  dropdown

De oplegreacties in punt A zijn:
\begin{align*}
A_x &= -85 \text{ kN} = 85 \text{ kN} \leftarrow \\
A_y &= 77.83 \text{ kN} \uparrow
\end{align*}


De oplegreacties in punt B zijn:
\begin{align*}
B_y &= -53.83 \text{ kN} = 53.83 \text{ kN} \downarrow
\end{align*}

````{admonition} Uitwerking
:class:  dropdown

Maak een VLS:

```{figure} ../figures/HC5_4vls.png
---
width: 70%
name: HC5_4vls
align: center
---
: Voorbeeld Opgave 4 - VLS
```

Stel de evenwichtsvergelijkingen op:

Horizontale krachtenvevenwicht geeft:
\begin{align}
\rightarrow_+ \Sigma{F_x} &= 0 \\
&= A_x + F_1 - q_x \cdot 5 + F_2 \\
&= A_x + 50 - 4 \cdot 5 + 55 \\
&= A_x + 85\\
A_x &= -85 \text{ kN} = 85 \text{ kN} \leftarrow
\end{align}


Momentenevenwicht geeft:
\begin{align}
\circlearrowleft_+ \Sigma{M_{|A}}  &= 0 \\
&=  - R_{q_z} \cdot 3 + F_{1} \cdot 2 - R_{qx} \cdot (2 + \dfrac{1}{2} \cdot 4) + F_{2} \cdot 7 + B_y \cdot 6 \\
&= - (\dfrac{1}{2} \cdot 6 \cdot 8) \cdot 3 + 50 \cdot 2 - ( 4 \cdot 5) \cdot (2 + \dfrac{1}{2} \cdot 5) + 55 \cdot 7 + B_y \cdot 6 \\
&= - 72 + 100 - 90 + 385 + B_y \cdot 6 \\
&= 323 + 6B_y \\
B_y &= \dfrac{323}{-6}\\
B_y &= -53.83 \text{ kN} = 53.83 \text{ kN} \downarrow
\end{align}


Verticale krachtenevenwicht geeft:
\begin{align}
\uparrow_+  \Sigma{F_y} &= 0 \\
&= A_y - R_{q_z} - B_y\\
&= A_y - 24 - 53.83\\
&= A_y - 77.83 \\
A_y &= 77.83 \text{ kN} \uparrow
\end{align}
````
`````

<hr style="border:1px solid #9EA700">
