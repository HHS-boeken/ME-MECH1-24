# Uitwerkingen

## Opgave 1

`````{admonition} Antwoord
:class:  dropdown

De oplegreacties in punt A zijn:
\begin{align*}
A_x &= -30 \text{ kN} = 30 \text{ kN} \leftarrow \\
A_y &= 15 \text{ kN} \uparrow \\
M_A &= 155 \text{ kNm} \circlearrowleft
\end{align*}


````{admonition} Uitwerking
:class:  dropdown

Maak een VLS:

```{figure} ../figures/WC5_1vls.png
---
width: 70%
name: WC5_1vls
align: center
---
: Voorbeeld Opgave 1 - VLS
```

Stel de evenwichtsvergelijkingen op:

Horizontale krachtenvevenwicht geeft:
\begin{align}
\rightarrow_+ \Sigma{F_x} &= 0 \\
&= A_x + R_{q2} \\
&= A_x + \dfrac{1}{2} \cdot 6 \cdot 10 \\
&= A_x + 30 \\
A_x &= -30 \text{ kN} = 30 \text{ kN} \leftarrow
\end{align}

Verticale krachtenevenwicht geeft:
\begin{align}
\uparrow_+  \Sigma{F_y} &= 0 \\
&= A_y - R_{q1} \\
&= A_y - \dfrac{1}{2} \cdot 6 \cdot 5 \\
&= A_y - 15 \\
A_y &= 15 \text{ kN} \uparrow \\
\end{align}

Momentenevenwicht geeft:
\begin{align}
\circlearrowleft_+ \Sigma{M_{|A}}  &= 0 \\
&= M_A - R_{q1} \cdot 3 - R_{q2} \cdot \left( \dfrac{1}{3} \cdot 6 \right) - T1 \\
&= M_A - \dfrac{1}{2} \cdot 6 \cdot 5 \cdot 3 - \dfrac{1}{2} \cdot 6 \cdot 10 \cdot \left( \dfrac{1}{3} \cdot 6 \right) - 50 \\
&= M_A - 45 - 60 -50 \\
&= M_A -155 \\
M_A &= 155 \text{ kNm} \circlearrowleft
\end{align}





````
`````

<hr style="border:1px solid #9EA700">

## Opgave 2

`````{admonition} Antwoord
:class:  dropdown

De oplegreacties in punt A zijn:
\begin{align*}
A_x &= 0 \text{ kN} \\
A_y &\approx 21.66 \text{ kN} \uparrow \\
B_y &\approx 63.33 \text{ kN} \uparrow
\end{align*}


````{admonition} Uitwerking
:class:  dropdown

Maak een VLS:

```{figure} ../figures/WC5_2vls.png
---
width: 70%
name: WC5_2vls
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
&= T_1 - R_{q_1} \cdot \left( \dfrac{1}{3} \cdot 6 \right)  - R_{q_2} \cdot 5 - T_2 + B_y \cdot 6     \\
&= 60 - \left( \dfrac{1}{2} \cdot 5 \cdot 6 \right) \cdot \left( \dfrac{1}{3} \cdot 6 \right)  - \left( 7 \cdot 10 \right) \cdot 5 - 60 + B_y \cdot 6     \\
&= 60 - 30  - 350 - 60 + 6B_y      \\
&= - 380 + 6B_y      \\
6B_y &= 380 \\
B_y &= \dfrac{380}{6} \\
B_y &\approx 63.33 \text{ kN} \uparrow
\end{align}


Verticale krachtenevenwicht geeft:
\begin{align}
\uparrow_+  \Sigma{F_y} &= 0 \\
&= A_y - R_{q_1} - R_{q_2} + B_y  \\
&= A_y - \left( \dfrac{1}{2} \cdot 5 \cdot 6 \right) -  \left( 7 \cdot 10 \right) + 63.33 \\
&= A_y - 85 + 63.33  \\
&= A_y - 21.66 \\
A_y &\approx 21.66 \text{ kN} \uparrow
\end{align}


````
`````

<hr style="border:1px solid #9EA700">


## Opgave 3

`````{admonition} Antwoord
:class:  dropdown

De oplegreacties in punt A zijn:
\begin{align*}
A_x &= 100 \text{ kN} \rightarrow \\
A_y &= 44.6 \text{ kN} \uparrow
\end{align*}


De oplegreacties in punt B zijn:
\begin{align*}
B_y &= -25.1 \text{ kN} = 25.1  \text{ kNm} \downarrow
\end{align*}

````{admonition} Uitwerking
:class:  dropdown

Maak een VLS:

```{figure} ../figures/WC5_3vls.png
---
width: 70%
name: WC5_3vls
align: center
---
: Voorbeeld Opgave 3 - VLS
```

Stel de evenwichtsvergelijkingen op:

Horizontale krachtenvevenwicht geeft:
\begin{align}
\rightarrow_+ \Sigma{F_x} &= 0 \\
&= A_x - R_{q_3} + F_{1} \\
&= A_x - 25 \cdot 6 +  50 \\
&= A_x - 100 \\
A_x &= 100 \text{ kN} \rightarrow
\end{align}

Momentenevenwicht geeft:
\begin{align}
\circlearrowleft_+ \Sigma{M_{|A}}  &= 0 \\
&= R_{q_3} \cdot 3 - R_{q_1} \cdot (\dfrac{1}{3} \cdot 3 ) - R_{q_2} \cdot (3+ \dfrac{2}{3} \cdot 3 )+ F_{1} \cdot (4+1) + B_y \cdot 6 \\
&= 25 \cdot 6 \cdot 3 - (\dfrac{1}{2} \cdot 3 \cdot 8) \cdot (\dfrac{1}{3} \cdot 3 ) - (\dfrac{1}{2} \cdot 3 \cdot 5) \cdot (3+ \dfrac{2}{3} \cdot 3 )+ 50 \cdot (4+1) + 6B_y  \\
&= 450 - 12 - 37.5 -250  + 6B_y\\
&= 150.5 + 6B_y\\
-6B_y &= 150.5 \\
B_y &= \dfrac{-150.5}{6} \\
B_y &= -25.1 \text{ kN} = 25.1  \text{ kNm} \downarrow
\end{align}

Verticale krachtenevenwicht geeft:
\begin{align}
\uparrow_+  \Sigma{F_y} &= 0 \\
&= A_y - R_{q_1} - R_{q_2} - B_y \\
&= A_y - (\dfrac{1}{2} \cdot 3 \cdot 8) - (\dfrac{1}{2} \cdot 3 \cdot 5) - 25.1 \\
&= A_y - 12 - 7.5  - 25.1 \\
&= A_y  - 44.6 \\
A_y &= 44.6 \text{ kN} \uparrow
\end{align}



````
`````

<hr style="border:1px solid #9EA700">

