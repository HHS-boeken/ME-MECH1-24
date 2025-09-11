# Uitwerkingen

<hr style="border:3px solid #9EA700">

## Opgave 1

````{admonition} Antwoord
:class:  dropdown

\begin{align*}
 |\overrightarrow{F_{1}}| &\approx -9.14 \text{ kN}
\end{align*}

\begin{align*}
 |\overrightarrow{F_{2}}| &\approx -9.32 \text{ kN}
\end{align*}

```{admonition} Uitwerking
:class:  dropdown

Maak een VLS:

Stel de evenwichtsvergelijkingen op en bepaal $|\overrightarrow{F_{1}}|$ en $|\overrightarrow{F_{2}}|$ :

\begin{align}
\Sigma{F_y} &= 0 \\
&= F_{2;y} +  F_{3;y} \\
&= |\overrightarrow{F_{2}}| \cdot \sin (25) + |\overrightarrow{F_{3}}| \cdot \sin (80)  \\
\\
|\overrightarrow{F_{2}}| \cdot \sin (25) &= - |\overrightarrow{F_{3}}| \cdot \sin (80) \\
|\overrightarrow{F_{2}}|  &= - |\overrightarrow{F_{3}}| \cdot \dfrac{\sin (80)}{\sin (25)}\\
&= -4 \cdot \dfrac{\sin (80)}{\sin (25)}\\
&\approx -9.32 \text{ kN}
\end{align}

\begin{align}
\Sigma{F_x} &= 0 \\
&= F_{1;x} +  F_{2;x} + F_{3;x}= 0 \\
&= |\overrightarrow{F_{1}}| - |\overrightarrow{F_{2}}| \cdot \cos (25) + |\overrightarrow{F_{3}}| \cdot \cos (80) \\
&= |\overrightarrow{F_{1}}| + 9.32 \cdot \cos (25) + 4 \cdot \cos (80) \\
&= |\overrightarrow{F_{1}}|+ 8.45 + 0.69 \\
&= |\overrightarrow{F_{1}}|+ 9.14 \\
\\
|\overrightarrow{F_{1}}| &\approx - 9.14  \text{ kN}\\
\end{align}
```
````

<hr style="border:1px solid #9EA700">

## Opgave 2

````{admonition} Antwoord
:class:  dropdown

\begin{align*}
 |\overrightarrow{F_{1}}| &\approx -9.14 \text{ kN}
\end{align*}

\begin{align*}
 |\overrightarrow{F_{2}}| &\approx -9.32 \text{ kN}
\end{align*}

```{admonition} Uitwerking
:class:  dropdown

Maak een VLS van punt C:

Stel de evenwichtsvergelijkingen op :

\begin{align}
\Sigma{F_y} &= 0 \\
&= F_{1;y} +  F_{3;y} \\
&= |\overrightarrow{F_{1}}| \cdot \sin (20) - |\overrightarrow{F_{3}}| \\
&= (60 \cdot 9.81) \cdot \sin (20) - |\overrightarrow{F_{3}}| \\
&= 588.6 \cdot \sin (20) - |\overrightarrow{F_{3}}| \\
&= 201.31 - |\overrightarrow{F_{3}}| \\
\\
|\overrightarrow{F_{3}}| &\approx 201.31 \text{ kN}\\
\end{align}
```
````

<hr style="border:1px solid #9EA700">

## Opgave 3

````{admonition} Antwoord
:class:  dropdown

\begin{align*}
 |\overrightarrow{F_{1}}| &\approx -9.14 \text{ kN}
\end{align*}

\begin{align*}
 |\overrightarrow{F_{2}}| &\approx -9.32 \text{ kN}
\end{align*}

```{admonition} Uitwerking
:class:  dropdown

Maak een VLS van punt C en punt B:



Bereken eerst de hoeken van het systeem

\begin{align}
\alpha &= arctan \left( \dfrac{40}{20}\right) = 63.4 \\
\beta &= arctan \left( \dfrac{50-40}{80}\right) = 7.13 \\
\phi &= arctan \left( \dfrac{50}{50}\right) = 45 \\
\end{align}

Stel de evenwichtsvergelijkingen op voor punt C:

\begin{align}
\Sigma{F_x} &= 0 \\
&= F_{1;x} + F_{2;x}  \\
&= -|\overrightarrow{F_{1}}| \cdot \cos (7.13) + |\overrightarrow{F_{2}}| \cdot \cos (45) \\
\\
|\overrightarrow{F_{1}}| \cdot \cos (7.13) &= |\overrightarrow{F_{2}}| \cdot \cos (45) \\
|\overrightarrow{F_{1}}| &= |\overrightarrow{F_{2}}| \cdot \dfrac{\cos (45)}{\cos(7.13)} \\
|\overrightarrow{F_{1}}| &= 0.71|\overrightarrow{F_{2}}|
\end{align}

\begin{align}
\Sigma{F_y} &= 0 \\
&= F_{1;y} + F_{2;y} + F_{3;y}  \\
&= |\overrightarrow{F_{1}}| \cdot \sin (7.13) + |\overrightarrow{F_{2}}| \cdot \sin (45) - W \\
&= |\overrightarrow{F_{1}}| \cdot \sin (7.13) + |\overrightarrow{F_{2}}| \cdot \sin (45) - 100 
\end{align}

$|\overrightarrow{F_{1}}|$ invullen geeft:
\begin{align}
0 &= |\overrightarrow{F_{1}}| \cdot \sin (7.13) + |\overrightarrow{F_{2}}| \cdot \sin (45) - 100 \\
 &= |\overrightarrow{F_{2}}| \cdot \dfrac{\cos (45)}{\cos(7.13)} \cdot \sin (7.13) + |\overrightarrow{F_{2}}| \cdot \sin (45) - 100 \\
 &= 0.088 |\overrightarrow{F_{2}}| + 0.707|\overrightarrow{F_{2}}| - 100 \\
 &= 0.795 |\overrightarrow{F_{2}}| - 100 \\
\\
0.795 |\overrightarrow{F_{2}}| &= 100 \\
|\overrightarrow{F_{2}}| &= \dfrac{100}{0.795} \\
 & \approx 125.77 \text{ N}
\end{align}

$|\overrightarrow{F_{2}}|$ invullen geeft:

\begin{align}
|\overrightarrow{F_{1}}| &= |\overrightarrow{F_{2}}| \cdot \dfrac{\cos (45)}{\cos(7.13)} \\
&= 125.77 \cdot \dfrac{\cos (45)}{\cos(7.13)} \\
&\approx 89.63 \text{ N}\
\end{align}

Stel de evenwichtsvergelijkingen op voor punt B:

\begin{align}
\Sigma{F_x} &= 0 \\
&= F_{1;x} + F_{4;x} + P_x  \\
0 &= |\overrightarrow{F_{1}}| \cdot \cos (7.13) - |\overrightarrow{F_{4}}| \cdot \cos (63.4) -  |\overrightarrow{P}| \cdot \cos (\theta)
\end{align}


$|\overrightarrow{F_{1}}| $ en $|\overrightarrow{F_{2}}| $ zijn gelijk vanwege de katrol, dit geeft:
\begin{align}
&= 89.63 \cdot \cos (7.13) - 89.63 \cdot \cos (63.4) -  |\overrightarrow{P}| \cdot \cos (\theta) \\
&= 48.8 - |\overrightarrow{P}| \cdot \cos (\theta) \\
|\overrightarrow{P}|  &= \dfrac{48.8}{\cos (\theta) }
\end{align}

\begin{align}
\Sigma{F_y} &= 0 \\
&= F_{1;y} + F_{4;y} + P_y  \\
0 &= -|\overrightarrow{F_{1}}| \cdot \sin (7.13) + |\overrightarrow{F_{4}}| \cdot \sin (63.4) -  |\overrightarrow{P}| \cdot \sin (\theta)
\end{align}


$|\overrightarrow{F_{1}}| $ en $|\overrightarrow{F_{2}}| $ zijn gelijk vanwege de katrol, dit geeft:
\begin{align}
&= -89.63 \cdot \sin (7.13) + 89.63 \cdot \sin (63.4) -  |\overrightarrow{P}| \cdot \sin (\theta) \\
&= 69.01 - |\overrightarrow{P}| \cdot \sin (\theta) \\
|\overrightarrow{P}|  &= \dfrac{69.01}{\sin (\theta) }
\end{align}

$|\overrightarrow{P}|$ invullen geeft:
\begin{align}
0 &= 69.01 - |\overrightarrow{P}| \cdot \sin (\theta) \\
 &= 69.01 - \dfrac{48.8}{\cos (\theta) } \cdot \sin (\theta) \\
&= 69.01 - 48.8 \cdot \tan (\theta) \\
48.8 \cdot \tan (\theta)  &= 69.01 \\
\tan (\theta)  &= \dfrac{69.01}{48.8} \\
\theta &= \arctan (\dfrac{69.01}{48.8}) \\
\theta &\approx 54.7
\end{align}

$\theta$ invullen geeft:
\begin{align}
|\overrightarrow{P}|  &= \dfrac{48.8}{\cos (\theta) } \\
&= \dfrac{48.8}{\cos (54.7) } \\
& \approx 84.4  \text{ N}
\end{align}
```
````

<hr style="border:1px solid #9EA700">