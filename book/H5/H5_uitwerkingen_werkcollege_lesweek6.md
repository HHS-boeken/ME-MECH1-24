# Uitwerkingen

## Opgave 1

`````{admonition} Antwoord
:class:  dropdown

De stijfheid $k$ van elke veer is:
\begin{align*}
    k &= 115.9 \text{ N/m}
\end{align*}


````{admonition} Uitwerking
:class:  dropdown

Maak een VLS:

<!-- ```{figure} ../figures/WC5_1vls.png
---
width: 70%
name: WC5_1vls
align: center
---
: Voorbeeld Opgave 1 - VLS
``` -->

Momentenevenwicht om punt $A$ geeft:
\begin{align}
\circlearrowleft_+ \Sigma{M_{|A}}  &= 0 \\
&= F_{veer;B} \cdot 2 - F_1 \cdot 3\\
&= F_{veer;B} \cdot 2 - 30 \cdot 3\\
&= F_{veer;B} \cdot 2 - 90 \\
-2 F_{veer;B} &= - 90 \\
F_{veer;B} &= \dfrac{-90}{-2} \\
F_{veer;B} &= 45 \text{ kN} \uparrow
\end{align}

Momentenevenwicht om punt $B$ geeft:
\begin{align}
\circlearrowleft_+ \Sigma{M_{|B}}  &= 0 \\
&= - F_{veer;A} \cdot 2 - F_1 \cdot 1\\
&= - F_{veer;A} \cdot 2 - 30 \cdot 1\\
&= - F_{veer;A} \cdot 2 - 30 \\
2 F_{veer;A} &= - 30 \\
F_{veer;A} &= \dfrac{-30}{2} \\
F_{veer;A} &= -15 \text{ kN} =15 \text{ kN} \downarrow
\end{align}

Gebruik de veer-formule.

In punt $A$ geeft dit;
\begin{align}
    F_{veer;A} &= k \cdot x_A \\
    x_A &= \dfrac{F_{veer;A}}{k} \\
    x_A &= \dfrac{15}{k}
\end{align}

In punt $B$ geeft dit:
\begin{align}
    F_{veer;B} &= k \cdot x_B \\
    x_B &= \dfrac{F_{veer;A}}{k} \\
    x_B &= \dfrac{45}{k}
\end{align}

Het gebruik van verhoudingen van driehoeken geeft:
\begin{align}
    \dfrac{d}{ \dfrac{45}{k}} &= \dfrac{2-d}{ \dfrac{15}{k}}
\end{align}

Met behulp van kruislingsvermenigvuldigen kan $d$ bepaald worden:
\begin{align}
    \dfrac{15}{k} \cdot d &= (2-d) \cdot \dfrac{45}{k} \\
    15 \cdot d &= (2-d) \cdot 45 \\
    15d &= 90 - 45d \\
    60d &= 90 \\
    d &= \dfrac{90}{60} \\
    d &= 1.5  \text{ m}
\end{align}

Uit de geometrie van driehoeken volgt $k$:
\begin{align}
    \sin (15) &= \dfrac{ \dfrac{45}{k} }{d} \\
    \sin (15) &= \dfrac{ \dfrac{45}{k} }{1.5} \\
    1.5 \cdot \sin (15) &= \dfrac{45}{k} \\
    k &= \dfrac{45}{1.5 \cdot \sin (15) } \\
    k &= 115.9 \text{ N/m}
\end{align}


````
`````

<hr style="border:1px solid #9EA700">

## Opgave 2

`````{admonition} Antwoord
:class:  dropdown

De lengte van touw $BC$ is:
\begin{align*}
    l_{BC} &= 1.32  \text{ m}
\end{align*}


````{admonition} Uitwerking
:class:  dropdown

Maak een VLS:

<!-- ```{figure} ../figures/WC5_1vls.png
---
width: 70%
name: WC5_1vls
align: center
---
: Voorbeeld Opgave 1 - VLS
``` -->

Stel de evenwichtsvergelijkingen op:

Horizontale krachtenvevenwicht geeft:
\begin{align}
    \rightarrow_+ \Sigma{F_x} &= 0 \\
    &= -F_{veer;AB} + T_{BC} \cdot \cos(30) \\
\end{align}

Verticale krachtenevenwicht geeft:
\begin{align}
    \uparrow_+  \Sigma{F_y} &= 0 \\
    &= -8 \cdot 9.81 + T_{BC} \cdot \sin(30) \\
    &= -78.48 + T_{BC} \cdot \sin(30) \\
    - T_{BC} \cdot \sin(30) &= -78.48 \\
    T_{BC} &= \dfrac{-78.48}{ -\sin(30) } \\
    T_{BC} &= 156.96 \text{ N}
\end{align}

$T_{BC}$ invullen geeft:
\begin{align}
    \rightarrow_+ \Sigma{F_x} &= 0 \\
    &= -F_{veer;AB} + T_{BC} \cdot \cos(30) \\
    &= -F_{veer;AB} + 156.96 \cdot \cos(30) \\
    F_{veer;AB} &= 156.96 \cdot \cos(30) \\
    F_{veer;AB} &= 135.93 \text{ N}
\end{align}

De uitrekking van de veer $AB$ is:
\begin{align}
    F_{veer;AB} &= k_{AB} \cdot x_{AB} \\
    x_{AB} &= \dfrac{F_{veer;AB} } {k_{AB}} \\
    x_{AB} &= \dfrac{135.93}{300} \\
    x_{AB} &= 0.453 \text{ m}
\end{align}

De uitgerekte lengte is dan:
\begin{align}
    l_{AB} &= l'_{AB} + x_{AB} \\
    l_{AB} &= 0.4 + 0.453 \\
    l_{AB} &= 0.853 \text{ m}
\end{align}

De horizontale afstand van $A$ naar $C$ is:
\begin{align}
    2 &= l_{AB} + l_{BC} \cdot \cos(30) \\
    2 &= 0.853 + l_{BC} \cdot \cos(30) \\
    2 - 0.853 &= l_{BC} \cdot \cos(30) \\
    1.147 &= l_{BC} \cdot \cos(30) \\
    l_{BC} &= \dfrac{1.147}{\cos(30)} \\
    l_{BC} &= 1.32  \text{ m}
\end{align}



````
`````

<hr style="border:1px solid #9EA700">


## Opgave 3

`````{admonition} Antwoord
:class:  dropdown

De massa $M$ van elke cilinder is:
\begin{align*}
    M &= 2.37  \text{ kg}
\end{align*}


````{admonition} Uitwerking
:class:  dropdown

Maak een VLS:

<!-- ```{figure} ../figures/WC5_1vls.png
---
width: 70%
name: WC5_1vls
align: center
---
: Voorbeeld Opgave 1 - VLS
``` -->

Vanwege symmetrie alleen het linkerdeel bekijken.

Als veer $AC$ niet vervormd heeft deze een lengte, $l'_{AC}$, van:
\begin{align}
    l'_{AC} &= \sqrt{2^2 + 1.5^2} \\
    &= 2.5 \text{ m}
\end{align}

In vervormde toetstand heeft veer $AC$ een lengte, $l_{AC}$, van:
\begin{align}
    l_{AC} &= \sqrt{2^2 + 2^2} \\
    &= 2.828 \text{ m}
\end{align}

Dus de uitrekking van veer $AC$, $x_{AC}$ is:
\begin{align}
    l_{AC} &= l'_{AC} + x_{AC}  \\
    x_{AC} &= l_{AC} - l'_{AC}  \\
    &= 2.828 - 2.5 \\
    &= 0.328 \text{ m}
\end{align}

De kracht in veer $AC$, F_{veer;AC} is:
\begin{align}
    F_{veer;AC} &= k \cdot x_{AC} \\
    &= 100 \cdot 0.328 \\
    &= 32.84 \text{ N}
\end{align}

Verticale krachtenevenwicht geeft:
\begin{align}
    \uparrow_+  \Sigma{F_y} &= 0 \\
    &= F_{veer;AC} \cdot \sin(45) - M \cdot 9.81 \\
    &= 32.84 \cdot \sin(45) - M \cdot 9.81 \\
    &= 23.22 - 9.81M \\
    9.81M &= 23.22 \\
    M &= \dfrac{23.22}{9.81} \\
    M &= 2.37  \text{ kg}
\end{align}



````
`````

<hr style="border:1px solid #9EA700">

