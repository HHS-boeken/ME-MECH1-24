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

