# Voorbeeldtoets MECH1-T2 - Uitwerkingen


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

Stap 1: Maak een VLS:


Stap 2: Bepaal de oplegreacties:

Horizontale krachtenvevenwicht geeft:
\begin{align}
\rightarrow_+ \Sigma{F_x} &= 0 \\
&= F_x =0 \quad {\color{blue}   \text{(1p)}} \\
\end{align}

Momentenevenwicht geeft:
\begin{align}
\circlearrowleft_+ \Sigma{M_{|D}}  &= 0 \\
&= -20 \cdot 3 - 12 \cdot 3 - 5 \cdot 6 + Fy \cdot 6 = 0  {\color{blue}   \text{(1p)}} \\
&= -126 + F_y \cdot 6 = 0 \\
F_y &= 21 \text{ kN} \uparrow \quad {\color{blue}   \text{(1p)}}
\end{align}

Verticale krachtenevenwicht geeft:
\begin{align}
\uparrow_+  \Sigma{F_y} &= 0 \\
&= 5 + 20 + 5 + 12 - F_y - F_D = 0  \quad {\color{blue}   \text{(1p)}} \\
&= 42 - 21 - F_D = 0 \\
&= 21 - F_D = 0 \\
F_D &= 21 \text{ kN} \uparrow \quad {\color{blue}   \text{(1p)}}
\end{align}

Stap 3: Bepaal de evenwicht per knoop
Knooppunt D:

Verticale krachtenevenwicht geeft:
\begin{align}
\uparrow_+  \Sigma{F_y} &= 0 \\
&= D_y + F_{AD} \quad {\color{blue}   \text{(1p)}} \\
&= 21 + F_{AD}\\
F_{AD}&= -21 \text{ kN} \\
F_{AD}&= 21 \text{ kN} \text{ (Druk)} \quad {\color{blue}   \text{(1p)}}
\end{align}

Horizontale krachtenvevenwicht geeft:
\begin{align}
\rightarrow_+ \Sigma{F_x} &= 0 \\
&= F_{DE} =0 \quad {\color{blue}   \text{(1p)}} \\
\end{align}

Knooppunt A:

Verticale krachtenevenwicht geeft:
\begin{align}
    \uparrow_+  \Sigma{F_y} &= 0 \\
    &= -5 + F_{AD} - F_{AE;y} \quad {\color{blue}   \text{(1p)}} \\
    &= -5 + 21 - F_{AE;y}\\
    F_{AE;y}&= 16 \text{ kN} \\
    F_{AE} &= \dfrac{1,6}{3,4} \cdot F_{AE;y} \\
    F_{AE} &= \dfrac{1,6}{3,4} \cdot 16 \\
    F_{AE}&= 34 \text{ kN} \text{ (Trek)} \quad {\color{blue}   \text{(1p)}}
\end{align}

Horizontale krachtenvevenwicht geeft:
\begin{align}
    \rightarrow_+ \Sigma{F_x} &= 0 \\
    &= F_{AB} + F_{AE;x}  \\
    &= F_{AB} +  \dfrac{3}{3,4} \cdot F_{AE}\\
    &= F_{AB} +  \dfrac{3}{3,4} \cdot 34\\
    F_{AB} &= -30 \text{ kN} \\
    F_{AB} &= 30 \text{ kN} \text{ (Druk)} \quad {\color{blue}   \text{(1p)}}
\end{align}

Knooppunt C:

Verticale krachtenevenwicht geeft:
\begin{align}
    \uparrow_+  \Sigma{F_y} &= 0 \\
    &= -5 - F_{CF}  \quad {\color{blue}   \text{(1p)}} \\
    F_{CF} &= -5  \text{ kN} \\
    F_{CF}&= 34 \text{ kN} \text{ (Druk)} \quad {\color{blue}   \text{(1p)}}
\end{align}

Horizontale krachtenvevenwicht geeft:
\begin{align}
\rightarrow_+ \Sigma{F_x} &= 0 \\
&= F_{BC} =0 \quad {\color{blue}   \text{(1p)}} \\
\end{align}

Knooppunt F:

Verticale krachtenevenwicht geeft:
\begin{align}
    \uparrow_+  \Sigma{F_y} &= 0 \\
    &= -5 + F_{AD} - F_{AE;y} \quad {\color{blue}   \text{(1p)}} \\
    &= -5 + 21 - F_{AE;y}\\
    F_{AE;y}&= 16 \text{ kN} \\
    F_{AE} &= \dfrac{1,6}{3,4} \cdot F_{AE;y} \\
    F_{AE} &= \dfrac{1,6}{3,4} \cdot 16 \\
    F_{AE}&= 34 \text{ kN} \text{ (Trek)} \quad {\color{blue}   \text{(1p)}}
\end{align}

Horizontale krachtenvevenwicht geeft:
\begin{align}
    \rightarrow_+ \Sigma{F_x} &= 0 \\
    &= F_{AB} + F_{AE;x}  \\
    &= F_{AB} +  \dfrac{3}{3,4} \cdot F_{AE}\\
    &= F_{AB} +  \dfrac{3}{3,4} \cdot 34\\
    F_{AB} &= -30 \text{ kN} \\
    F_{AB} &= 30 \text{ kN} \text{ (Druk)} \quad {\color{blue}   \text{(1p)}}
\end{align}




Horizontale krachtenvevenwicht geeft:
\begin{align}
    \rightarrow_+ \Sigma{F_x} &= 0 \\
    &= F_{AB} + F_{AE;x}  \\
    &= F_{AB} +  \dfrac{3}{3,4} \cdot F_{AE}\\
    &= F_{AB} +  \dfrac{3}{3,4} \cdot 34\\
    F_{AB} &= -30 \text{ kN} \\
    F_{AB} &= 30 \text{ kN} \text{ (Druk)} \quad {\color{blue}   \text{(1p)}}
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



````
`````

<hr style="border:1px solid #9EA700">