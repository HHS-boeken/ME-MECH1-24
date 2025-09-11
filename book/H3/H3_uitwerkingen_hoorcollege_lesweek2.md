# Uitwerkingen

## Terugblik Opgave 1

````{admonition} Antwoord
:class:  dropdown


\begin{align*}
|\overrightarrow{F_{res}}| = 37.53 \text{ N}
\end{align*}

\begin{align*}
\phi = 19.6 \text{ graden}
\end{align*}


```{admonition} Uitwerking
:class:  dropdown

Ontbind de kracht $\overrightarrow{F_1}$ in $F_{1;x}$ en $F_{1;y}$ :
\begin{align}
\dfrac{F_1;x}{4} &= \dfrac{|\overrightarrow{F_1}|}{5} \\
F_{1;x} &=  |\overrightarrow{F_1}| \cdot \dfrac{4}{5} \\
& = 50 \cdot \dfrac{4}{5} \\
& = 40 \text{ kN} \rightarrow
\end{align}

\begin{align}
\dfrac{F_1;y}{3} &= \dfrac{|\overrightarrow{F_1}|}{5} \\
F_{1;y} &=  |\overrightarrow{F_1}| \cdot \dfrac{3}{5} \\
& = 50 \cdot \dfrac{3}{5} \\
& = 30 \text{ kN} \uparrow
\end{align}


Ontbind de kracht $\overrightarrow{F_2}$ in $F_{2;x}$ en $F_{2;y}$ :
\begin{align}
\dfrac{F_2;x}{1} &= \dfrac{|\overrightarrow{F_2}|}{\sqrt{10}} \\
F_{2;x} &=  |\overrightarrow{F_1}| \cdot \dfrac{1}{\sqrt{10}} \\
& = 30 \cdot \dfrac{1}{\sqrt{10}} \\
& \approx 9.49 \text{ kN} \rightarrow
\end{align}

\begin{align}
\dfrac{F_2;y}{3} &= \dfrac{|\overrightarrow{F_2}|}{\sqrt{10}} \\
F_{2;y} &= - |\overrightarrow{F_1}| \cdot \dfrac{3}{\sqrt{10}} \\
& = - 30 \cdot \dfrac{3}{\sqrt{10}} \\
& \approx - 28.46 \text{ kN} \downarrow
\end{align}

Ontbind de kracht $\overrightarrow{F3}$ in $F_{3;x}$ en $F_{3;y}$ :
\begin{align}
F_{3;x} &=  - |\overrightarrow{F_3}| \cdot \cos (45) \\
& = - 20 \cdot \cos (45) \\
& \approx - 14.14 \text{ N} \leftarrow
\end{align}

\begin{align}
F_{3;y} &=  - |\overrightarrow{F_3}| \cdot \sin (45) \\
& = - 20 \cdot \sin (45) \\
& \approx - 14.14 \text{ N} \downarrow
\end{align}

Bepaal de resultante kracht $F_{res;x}$:
\begin{align}
F_{res;x} &=  F_{1;x} + F_{2;x} + F_{3;x} \\
& = 40 + 9.49 - 14.14  \\
& \approx 35.35 \text{ kN} \rightarrow
\end{align}

Bepaal de resultante kracht $F_{res;y}$:
\begin{align}
F_{res;y} &=  F_{1;y} + F_{2;y} + F_{2;y} \\
& = 30 - 28.46 - 14.14 \\
& \approx -12.6 \text{ N} \downarrow
\end{align}

Bepaal de grootte van de resultante kracht $\overrightarrow{F_{res}}$:
\begin{align}
|\overrightarrow{F_{res}}| &= \sqrt{(F_{res;x})^2 + (F_{res;y})^2 } \\
& = \sqrt{ (35.35)^2 + (12.6)^2 } \\
& \approx 37.53 \text{ kN}
\end{align}

Bepaal de richting van de resultante kracht  $\overrightarrow{F_{res}}$:
\begin{align}
\tan (\phi) &= \dfrac{F_{res;y}}{F_{res;x}} \\
\phi &=  \arctan (\dfrac{F_{res;y}}{F_{res;x}}) \\
\phi &=  \arctan (\dfrac{ 12.6}{ 35.35}) \\
& \approx 19.6 \text{ graden}
\end{align}
```
````

<hr style="border:1px solid #9EA700">

## Voorbeeld Opgave 1

````{admonition} Antwoord
:class:  dropdown


\begin{align*}
 |\overrightarrow{F_{1}}| &\approx 705.8  \text{ N}
\end{align*}

\begin{align*}
 |\overrightarrow{F_{2}}| &\approx 817.6 \text{ N}
\end{align*}


```{admonition} Uitwerking
:class:  dropdown

Maak een VLS:


Stel de evenwichtsvergelijkingen op en bepaal $|\overrightarrow{F_{1}}|$ en $|\overrightarrow{F_{1}}|$ :

\begin{align}
\Sigma{F_x} &= 0 \\
&= F_{1;x} +  F_{2;x} = 0 \\
&= - |\overrightarrow{F_{1}}| \cdot \cos (35) + |\overrightarrow{F_{2}}| \cdot \cos (45) \\
\\
|\overrightarrow{F_{1}}| \cdot \cos (35) &= |\overrightarrow{F_{2}}| \cdot \cos (45) \\
|\overrightarrow{F_{2}}|  &= |\overrightarrow{F_{1}}| \cdot \dfrac{\cos (35)}{\cos (45)}
\end{align}

\begin{align}
\Sigma{F_x} &= 0 \\
&= F_{1;y} +  F_{2;y} + F_3  \\
&= |\overrightarrow{F_{1}}| \cdot \sin (35) + |\overrightarrow{F_{2}}| \cdot \sin (45) - (100 \cdot 9.81)   \\
\end{align}

$|\overrightarrow{F_{2}}|$ invullen geeft:
\begin{align}
0 &= |\overrightarrow{F_{1}}| \cdot \sin (35) + |\overrightarrow{F_{2}}| \cdot \sin (45) - (100 \cdot 9.81) \\
 &= |\overrightarrow{F_{1}}| \cdot \sin (35) + |\overrightarrow{F_{1}}| \cdot \dfrac{\cos (35)}{\cos (45)} \cdot \sin (45) - (100 \cdot 9.81) \\
&= |\overrightarrow{F_{1}}|  \cdot 0.57 + |\overrightarrow{F_{1}}| \cdot 0.82 - 981 \\
&= 1.35|\overrightarrow{F_{1}}|  -  981 \\
|\overrightarrow{F_{1}}|  & = \dfrac{981}{1.39} \\
& \approx 705.8 \text{ N}
\end{align}

$|\overrightarrow{F_{1}}|$ invullen geeft:
\begin{align}
|\overrightarrow{F_{2}}|  &= |\overrightarrow{F_{1}}| \cdot \dfrac{\cos (35)}{\cos (45)} \\
&= 705.8 \cdot \dfrac{\cos (35)}{\cos (45)} \\
& \approx 817.6 \text{ N}
\end{align}





```
````

<hr style="border:1px solid #9EA700">
