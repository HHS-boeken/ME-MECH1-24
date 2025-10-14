# Uitwerkingen Voorbeeldtoets

## Opgave 1

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

a) Maak een VLS:

```{figure} figures/WC5_3vls.png
---
width: 70%
name: WC5_3vls
align: center
---
: Voorbeeld Opgave 1 - VLS
```

b) Stel de evenwichtsvergelijkingen op:

Horizontale krachtenvevenwicht geeft:
\begin{align}
\rightarrow_+ \Sigma{F_x} &= 0 \\
&= A_x - R_{q_3} + F_{1} \quad {\color{blue}   \text{(1p)}} \\
\end{align}

Momentenevenwicht geeft:
\begin{align}
\circlearrowleft_+ \Sigma{M_{|A}}  &= 0 \\
&= R_{q_3} \cdot 3 - R_{q_1} \cdot (\dfrac{1}{3} \cdot 3 ) - R_{q_2} \cdot (3+ \dfrac{2}{3} \cdot 3 )+ F_{1} \cdot (4+1) + B_y \cdot 6 \quad {\color{blue}   \text{(1p)}} \\
\end{align}

Verticale krachtenevenwicht geeft:
\begin{align}
\uparrow_+  \Sigma{F_y} &= 0 \\
&= A_y - R_{q_1} - R_{q_2} - B_y \quad {\color{blue}   \text{(1p)}} \\
\end{align}



b) Bereken de reacties:

Horizontale krachtenvevenwicht geeft:
\begin{align}
\rightarrow_+ \Sigma{F_x} &= 0 \\
&= A_x - R_{q_3} + F_{1} \\
&= A_x - 25 \cdot 6 +  50 \quad {\color{blue}   \text{(1p)}} \\
&= A_x - 100 \\
A_x &= 100 \text{ kN} \rightarrow \quad {\color{blue}   \text{(1p)}}
\end{align}

Momentenevenwicht geeft:
\begin{align}
\circlearrowleft_+ \Sigma{M_{|A}}  &= 0 \\
&= R_{q_3} \cdot 3 - R_{q_1} \cdot (\dfrac{1}{3} \cdot 3 ) - R_{q_2} \cdot (3+ \dfrac{2}{3} \cdot 3 )+ F_{1} \cdot (4+1) + B_y \cdot 6 \\
&= 25 \cdot 6 \cdot 3 - (\dfrac{1}{2} \cdot 3 \cdot 8) \cdot (\dfrac{1}{3} \cdot 3 ) - (\dfrac{1}{2} \cdot 3 \cdot 5) \cdot (3+ \dfrac{2}{3} \cdot 3 )+ 50 \cdot (4+1) + 6B_y  \quad {\color{blue}   \text{(1p)}} \\
&= 450 - 12 - 37.5 -250  + 6B_y\\
&= 150.5 + 6B_y\\
-6B_y &= 150.5 \\
B_y &= \dfrac{-150.5}{6} \\
B_y &= -25.1 \text{ kN} = 25.1  \text{ kNm} \downarrow \quad {\color{blue}   \text{(1p)}}
\end{align}

Verticale krachtenevenwicht geeft:
\begin{align}
\uparrow_+  \Sigma{F_y} &= 0 \\
&= A_y - R_{q_1} - R_{q_2} - B_y \\
&= A_y - (\dfrac{1}{2} \cdot 3 \cdot 8) - (\dfrac{1}{2} \cdot 3 \cdot 5) - 25.1 \quad {\color{blue}   \text{(1p)}} \\
&= A_y - 12 - 7.5  - 25.1 \\
&= A_y  - 44.6 \\
A_y &= 44.6 \text{ kN} \uparrow \quad {\color{blue}   \text{(1p)}}
\end{align}

````
`````

<hr style="border:1px solid #9EA700">

## Opgave 2

````{admonition} Antwoord
:class:  dropdown

\begin{align*}
 \text{ De resulterende kracht } F_{res} = 21.4 \text{ kN}
\end{align*}

\begin{align*}
 \text{ De werklijn van de kracht snijdt de x-as op } -12.97 \text{ m}
\end{align*}

```{admonition} Uitwerking
:class:  dropdown

Maak een VLS:


Stel de evenwichtsvergelijkingen op voor punt C:

Bepaal de resultante kracht $F_{res;x}$:
\begin{align}
\rightarrow_+ F_{res;x} &= \Sigma{F_x} \\
\Sigma{F_x} &= F_{2;x}   \\
&= |\overrightarrow{F_{2}}| \cdot \cos(70) \\
&= 50 \cdot \cos (70) \\
&\approx 17.1 \text{ kN}
\end{align}

Bepaal de resultante kracht $F_{res;y}$:
\begin{align}
\uparrow_+ F_{res;y} &= \Sigma{F_y} \\
\Sigma{F_x} &= F_{1;y} + F_{2;y}   \\
&= - F_{1} + |\overrightarrow{F_{2}}| \cdot \sin(70)   \\
&= - 60 + 50 \cdot \sin (70) \\
&\approx -13.02 \text{ kN} \\
&\approx 13.02 \text{ kN} \downarrow
\end{align}

Bepaal de grootte van de resultante kracht $\overrightarrow{F_{res}}$:
\begin{align}
|\overrightarrow{F_{res}}| &= \sqrt{(F_{res;x})^2 + (F_{res;y})^2 } \\
& = \sqrt{ (17.10)^2 + (-13.02)^2 } \\
& \approx 21.4 \text{ kN}
\end{align}

Bepaal de richting van de resultante kracht  $\overrightarrow{F_{res}}$:
\begin{align}
\tan (\phi) &= \dfrac{F_{res;y}}{F_{res;x}} \\
\phi &=  \arctan \left( \dfrac{F_{res;y}}{F_{res;x}} \right) \\
\phi &=  \arctan \left( \dfrac{ 13.02}{ 17.10} \right) \\
&\approx 37.3^{\circ}
\end{align}

\begin{align}
\circlearrowleft_+ \Sigma{M_{|A}}  &= - F_{1} \cdot d_{1;x} + F_{2;x} \cdot d_{2;y} + F_{2;y} \cdot d_{2;x} + T \\
&= - 60 \cdot 3 + 50 \cos(70) \cdot 0 + 50 \sin(70) \cdot 7 + 20 \\
&= - 180 + 0 + 328.89 + 20 \\
&= 168.89 \text{ kNm} = 168.89 \text{ kNm} \circlearrowleft\\
\end{align}

\begin{align}
M_R &= \Sigma{M_{|A}} \\
F_{res;y} \cdot d &= \Sigma{M_{|A}} \\
-13.02 \cdot d &= 168.89 \\
d &= \dfrac{168.89}{-13.02}\\
d &= -12.97 \text{ m}
\end{align}


```
````

<hr style="border:1px solid #9EA700">