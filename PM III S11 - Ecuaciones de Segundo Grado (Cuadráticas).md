> [!info]+ Contexto
> Una **ecuación de segundo grado** o **ecuación cuadrática** es aquella en la que el mayor exponente de la incógnita es $2$. Su forma general es:
> $$ax^2 + bx + c = 0$$
> donde $a, b$ y $c$ son números reales, y **$a \neq 0$** (si $a = 0$, la ecuación se convierte en lineal).
> 
> El objetivo al resolver una ecuación cuadrática es encontrar sus **raíces** o **soluciones**, es decir, los valores de $x$ que hacen que la igualdad sea verdadera.

# 1️⃣ Ecuaciones Cuadráticas Puras y Mixtas 
## A) Ecuaciones Cuadráticas Puras $ax^2 + c = 0$
> [!note]+ Definición y Procedimiento
> Una ecuación cuadrática es **pura** cuando carece del término lineal, es decir, tiene la forma:
> $$ax^2 + c = 0$$
> 
> **Procedimiento (usando valor absoluto):**
> 1. Despejar el término cuadrático: $x^2$.
> 2. Obtener la raíz cuadrada de ambos miembros de la ecuación.
> 3. Resolver la ecuación con valor absoluto que resulta.

> [!tip]+ Método Alternativo: Por Factorización (Diferencia de Cuadrados)
> Las ecuaciones puras también se pueden resolver factorizando como una **diferencia de cuadrados**: $a^2 - b^2 = (a - b)(a + b)$.
> Por ejemplo, para $x^2 - 64 = 0$:
> $$x^2 - 8^2 = 0 \implies (x - 8)(x + 8) = 0$$
> Igualando a cero cada factor: $x - 8 = 0 \Rightarrow x = 8$ y $x + 8 = 0 \Rightarrow x = -8$.

> [!EXAMPLE]- Actividad 1. Ejercicios de Ecuaciones Puras, pág. 133 y 134.
> 
> **Ejercicio 7:** $x^2 - 64 = 0$
>>[!SUCCESS]- Solución
>> $$ \begin{aligned}
>> x^2 &= 64 \\
>> \sqrt{x^2} &= \sqrt{64} \\
>> |x| &= 8 \\
>> x_1 &= 8, \quad x_2 = -8
>> \end{aligned} $$
>
> **Ejercicio 8:** $2x^2 - 98 = 0$
>>[!SUCCESS]- Solución
>> $$ \begin{aligned}
>> 2x^2 &= 98 \\
>> x^2 &= 49 \\
>> |x| &= \sqrt{49} \\
>> |x| &= 7 \\
>> x_1 &= 7, \quad x_2 = -7
>> \end{aligned} $$
>
> **Ejercicio 9:** $2x^2 - 72 = 0$
>>[!SUCCESS]- Solución
>> $$ \begin{aligned}
>> 2x^2 &= 72 \\
>> x^2 &= 36 \\
>> |x| &= 6 \\
>> x_1 &= 6, \quad x_2 = -6
>> \end{aligned} $$
>
> **Ejercicio 10:** $2x^2 - 50 = 0$
>>[!SUCCESS]- Solución
>> $$ \begin{aligned}
>> 2x^2 &= 50 \\
>> x^2 &= 25 \\
>> |x| &= 5 \\
>> x_1 &= 5, \quad x_2 = -5
>> \end{aligned} $$
>
> **Ejercicio 11:** $3x^2 - 48 = 0$
>>[!SUCCESS]- Solución
>> $$ \begin{aligned}
>> 3x^2 &= 48 \\
>> x^2 &= 16 \\
>> |x| &= 4 \\
>> x_1 &= 4, \quad x_2 = -4
>> \end{aligned} $$
>
> **Ejercicio 12:** $5x^2 - 245 = 0$
>>[!SUCCESS]- Solución
>> $$ \begin{aligned}
>> 5x^2 &= 245 \\
>> x^2 &= 49 \\
>> |x| &= 7 \\
>> x_1 &= 7, \quad x_2 = -7
>> \end{aligned} $$
## B) Ecuaciones Cuadráticas Mixtas $ax^2 + bx = 0$

> [!note]+ Definición y Procedimiento
> Una ecuación cuadrática es **mixta** cuando carece del término independiente, es decir, tiene la forma:
> $$ax^2 + bx = 0$$
> 
> **Procedimiento para resolverla (por factorización):**
> 1. Extraer el factor común $x$: $x(ax + b) = 0$.
> 2. Aplicar la propiedad del producto nulo (si $A \cdot B = 0$, entonces $A=0$ o $B=0$).
> 3. Igualar cada factor a cero y resolver:
>    - $x_1 = 0$
>    - $ax + b = 0 \Rightarrow x_2 = -\frac{b}{a}$
> 
> *Nota: En este tipo de ecuaciones, una de las soluciones siempre es cero.*

> [!EXAMPLE]- Actividad 1. Ejercicios de Ecuaciones Mixtas, pág. 133.
> 
> **Ejercicio 1:** $x^2 + 6x = 0$
>>[!SUCCESS]- Solución
>> $$ \begin{aligned}
>> x(x + 6) &= 0 \\
>> x_1 &= 0 \\
>> x + 6 = 0 &\Rightarrow x_2 = -6
>> \end{aligned} $$
>
> **Ejercicio 2:** $2x^2 - 14x = 0$
>>[!SUCCESS]- Solución
>> $$ \begin{aligned}
>> 2x(x - 7) &= 0 \\
>> 2x = 0 &\Rightarrow x_1 = 0 \\
>> x - 7 = 0 &\Rightarrow x_2 = 7
>> \end{aligned} $$
>
> **Ejercicio 3:** $x^2 - x = 0$
>>[!SUCCESS]- Solución
>> $$ \begin{aligned}
>> x(x - 1) &= 0 \\
>> x_1 &= 0 \\
>> x - 1 = 0 &\Rightarrow x_2 = 1
>> \end{aligned} $$
>
> **Ejercicio 4:** $5x^2 + 15x = 0$
>>[!SUCCESS]- Solución
>> $$ \begin{aligned}
>> 5x(x + 3) &= 0 \\
>> 5x = 0 &\Rightarrow x_1 = 0 \\
>> x + 3 = 0 &\Rightarrow x_2 = -3
>> \end{aligned} $$
>
> **Ejercicio 5:** $4x^2 - 20x = 0$
>>[!SUCCESS]- Solución
>> $$ \begin{aligned}
>> 4x(x - 5) &= 0 \\
>> 4x = 0 &\Rightarrow x_1 = 0 \\
>> x - 5 = 0 &\Rightarrow x_2 = 5
>> \end{aligned} $$
>
> **Ejercicio 6:** $2x^2 + x = 0$
>>[!SUCCESS]- Solución
>> $$ \begin{aligned}
>> x(2x + 1) &= 0 \\
>> x_1 &= 0 \\
>> 2x + 1 = 0 &\Rightarrow 2x = -1 \Rightarrow x_2 = -\frac{1}{2}
>> \end{aligned} $$
# 2️⃣ Resolución de $(ax + b)^2 = c$

> [!note]+ Definición y Procedimiento
> Son ecuaciones que ya se encuentran expresadas como un **binomio al cuadrado** igualado a una constante.
> 
> **Procedimiento:**
> 1. Extraer la raíz cuadrada en ambos miembros de la ecuación. Recordando que $\sqrt{u^2} = |u|$, tenemos:
>    $$\sqrt{(ax + b)^2} = \sqrt{c}$$
>    $$|ax + b| = \sqrt{c}$$
> 2. Por definición de valor absoluto, esto genera un signo $\pm$ en el miembro de la constante:
>    $$ax + b = \pm\sqrt{c}$$
> 3. Plantear las dos ecuaciones lineales resultantes y despejar $x$ en cada una.

> [!EXAMPLE]- Actividad 2. Ejercicios de Binomio al Cuadrado, pág. 135
> 
> **Ejercicio 1:** $(2x - 3)^2 = 81$
>>[!SUCCESS]- Solución
>> $$ \begin{aligned}
>> |2x - 3| &= \sqrt{81} \\
>> |2x - 3| &= 9 \\
>> \text{Caso 1: } 2x - 3 &= 9 \Rightarrow 2x = 12 \Rightarrow x_1 = 6 \\
>> \text{Caso 2: } 2x - 3 &= -9 \Rightarrow 2x = -6 \Rightarrow x_2 = -3
>> \end{aligned} $$
>
> **Ejercicio 2:** $(4x + 1)^2 = 49$
>>[!SUCCESS]- Solución
>> $$ \begin{aligned}
>> |4x + 1| &= 7 \\
>> 4x + 1 = 7 &\Rightarrow 4x = 6 \Rightarrow x_1 = \frac{3}{2} \\
>> 4x + 1 = -7 &\Rightarrow 4x = -8 \Rightarrow x_2 = -2
>> \end{aligned} $$
>
> **Ejercicio 3:** $(3x + 2)^2 = 100$
>>[!SUCCESS]- Solución
>> $$ \begin{aligned}
>> |3x + 2| &= 10 \\
>> 3x + 2 = 10 &\Rightarrow 3x = 8 \Rightarrow x_1 = \frac{8}{3} \\
>> 3x + 2 = -10 &\Rightarrow 3x = -12 \Rightarrow x_2 = -4
>> \end{aligned} $$
>
> **Ejercicio 4:** $(5x - 2)^2 = 144$
>>[!SUCCESS]- Solución
>> $$ \begin{aligned}
>> |5x - 2| &= 12 \\
>> 5x - 2 = 12 &\Rightarrow 5x = 14 \Rightarrow x_1 = \frac{14}{5} \\
>> 5x - 2 = -12 &\Rightarrow 5x = -10 \Rightarrow x_2 = -2
>> \end{aligned} $$
>
> **Ejercicio 5:** $(3x - 1)^2 = -64$
>>[!SUCCESS]- Solución
>> $$ \begin{aligned}
>> |3x - 1| &= \sqrt{-64}
>> \end{aligned} $$
>> Como la raíz cuadrada de un número negativo no existe en los números reales, **la ecuación no tiene solución real**.
>
> **Ejercicio 6:** $(3x + 6)^2 = 0$
>>[!SUCCESS]- Solución
>> $$ \begin{aligned}
>> |3x + 6| &= 0 \\
>> 3x + 6 &= 0 \Rightarrow 3x = -6 \Rightarrow x = -2
>> \end{aligned} $$
>> (Se obtiene una única solución o raíz doble).
>
> **Ejercicio 7:** $(6 - 2x)^2 = 16$
>>[!SUCCESS]- Solución
>> $$ \begin{aligned}
>> |6 - 2x| &= 4 \\
>> 6 - 2x = 4 &\Rightarrow -2x = -2 \Rightarrow x_1 = 1 \\
>> 6 - 2x = -4 &\Rightarrow -2x = -10 \Rightarrow x_2 = 5
>> \end{aligned} $$
>
> **Ejercicio 8:** $(4 - x)^2 = -9$
>>[!SUCCESS]- Solución
>> $$ \begin{aligned}
>> |4 - x| &= \sqrt{-9}
>> \end{aligned} $$
>> Al igual que en el ejercicio 5, **no hay solución real**.
# 3️⃣ Resolución de Ecuaciones Cuadráticas Completas $ax^2 + bx + c = 0$

> [!note]+ Definición
> Una ecuación cuadrática es **completa** cuando contiene los tres términos (cuadrático, lineal e independiente), es decir, tiene la forma general:
> $$ax^2 + bx + c = 0 \quad \text{con } a \neq 0, b \neq 0, c \neq 0$$
## A) Por Factorización

> [!note]+ Procedimiento
> Consiste en expresar el trinomio $ax^2 + bx + c$ como el producto de dos binomios. 
> 1. Buscar dos números que **multiplicados** den el término independiente ($c$) y **sumados** den el coeficiente lineal ($b$).
> 2. Escribir la factorización: $(x + m)(x + n) = 0$.
> 3. Igualar cada binomio a cero.

> [!EXAMPLE]- Actividad 3. Ejercicios de Factorización, pág. 138
> 
> **Ejercicio 1:** $x^2 - 5x + 6 = 0$
>>[!SUCCESS]- Solución
>> Buscamos dos números que multiplicados den $6$ y sumados den $-5$: son $-2$ y $-3$.
>> $$ \begin{aligned}
>> (x - 2)(x - 3) &= 0 \\
>> x - 2 = 0 &\Rightarrow x_1 = 2 \\
>> x - 3 = 0 &\Rightarrow x_2 = 3
>> \end{aligned} $$
>
> **Ejercicio 2:** $x^2 - 3x - 10 = 0$
>>[!SUCCESS]- Solución
>> Números que multiplicados den $-10$ y sumados den $-3$: son $-5$ y $2$.
>> $$ \begin{aligned}
>> (x - 5)(x + 2) &= 0 \\
>> x - 5 = 0 &\Rightarrow x_1 = 5 \\
>> x + 2 = 0 &\Rightarrow x_2 = -2
>> \end{aligned} $$
>
> **Ejercicio 3:** $x^2 + x - 20 = 0$
>>[!SUCCESS]- Solución
>> $$ \begin{aligned}
>> (x + 5)(x - 4) &= 0 \\
>> x + 5 = 0 &\Rightarrow x_1 = -5 \\
>> x - 4 = 0 &\Rightarrow x_2 = 4
>> \end{aligned} $$
>
> **Ejercicio 4:** $x^2 + 3x - 4 = 0$
>>[!SUCCESS]- Solución
>> $$ \begin{aligned}
>> (x + 4)(x - 1) &= 0 \\
>> x + 4 = 0 &\Rightarrow x_1 = -4 \\
>> x - 1 = 0 &\Rightarrow x_2 = 1
>> \end{aligned} $$
>
> **Ejercicio 5:** $x^2 - 2x - 24 = 0$
>>[!SUCCESS]- Solución
>> $$ \begin{aligned}
>> (x - 6)(x + 4) &= 0 \\
>> x - 6 = 0 &\Rightarrow x_1 = 6 \\
>> x + 4 = 0 &\Rightarrow x_2 = -4
>> \end{aligned} $$
>
> **Ejercicio 6:** $x^2 - 8x + 16 = 0$
>>[!SUCCESS]- Solución
>> Es un trinomio cuadrado perfecto:
>> $$ \begin{aligned}
>> (x - 4)^2 &= 0 \\
>> x - 4 = 0 &\Rightarrow x = 4
>> \end{aligned} $$
>> (Raíz doble).
## B) Completación de un Trinomio Cuadrado Perfecto

> [!note]+ Procedimiento
> 1. Si $a \neq 1$, dividir toda la ecuación entre $a$.
> 2. Pasar el término independiente al miembro derecho.
> 3. Sumar en ambos miembros el cuadrado de la mitad del coeficiente lineal: $\left(\frac{b}{2}\right)^2$.
> 4. Factorizar como un binomio al cuadrado y resolver.

> [!EXAMPLE]- Actividad 4. Ejercicios de Completar, pág. 140
> 
> **Ejercicio 1:** $x^2 + 6x - 16 = 0$
>>[!SUCCESS]- Solución
>> $$ \begin{aligned}
>> x^2 + 6x &= 16 \\
>> x^2 + 6x + \left(\frac{6}{2}\right)^2 &= 16 + 9 \\
>> x^2 + 6x + 9 &= 25 \\
>> (x + 3)^2 &= 25 \\
>> |x + 3| &= 5 \\
>> x + 3 = 5 &\Rightarrow x_1 = 2 \\
>> x + 3 = -5 &\Rightarrow x_2 = -8
>> \end{aligned} $$
>
> **Ejercicio 2:** $x^2 - 8x - 20 = 0$
>>[!SUCCESS]- Solución
>> $$ \begin{aligned}
>> x^2 - 8x &= 20 \\
>> x^2 - 8x + (-4)^2 &= 20 + 16 \\
>> (x - 4)^2 &= 36 \\
>> |x - 4| &= 6 \\
>> x - 4 = 6 &\Rightarrow x_1 = 10 \\
>> x - 4 = -6 &\Rightarrow x_2 = -2
>> \end{aligned} $$
>
> **Ejercicio 3:** $3x^2 - 24x + 45 = 0$
>>[!SUCCESS]- Solución
>> Dividimos entre $3$:
>> $$ \begin{aligned}
>> x^2 - 8x + 15 &= 0 \\
>> x^2 - 8x &= -15 \\
>> x^2 - 8x + 16 &= -15 + 16 \\
>> (x - 4)^2 &= 1 \\
>> |x - 4| &= 1 \\
>> x - 4 = 1 &\Rightarrow x_1 = 5 \\
>> x - 4 = -1 &\Rightarrow x_2 = 3
>> \end{aligned} $$
>
> **Ejercicio 4:** $2x^2 - 11x + 15 = 0$
>>[!SUCCESS]- Solución
>> Dividimos entre $2$:
>> $$ \begin{aligned}
>> x^2 - \frac{11}{2}x + \frac{15}{2} &= 0 \\
>> x^2 - \frac{11}{2}x &= -\frac{15}{2} \\
>> x^2 - \frac{11}{2}x + \left(\frac{11}{4}\right)^2 &= -\frac{15}{2} + \frac{121}{16} \\
>> \left(x - \frac{11}{4}\right)^2 &= \frac{-120 + 121}{16} = \frac{1}{16} \\
>> |x - \frac{11}{4}| &= \frac{1}{4} \\
>> x - \frac{11}{4} = \frac{1}{4} &\Rightarrow x_1 = \frac{12}{4} = 3 \\
>> x - \frac{11}{4} = -\frac{1}{4} &\Rightarrow x_2 = \frac{10}{4} = \frac{5}{2}
>> \end{aligned} $$
## C) La Fórmula General

> [!note]+ Procedimiento
> Para la ecuación $ax^2 + bx + c = 0$, la fórmula general es:
> $$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$
> **Discriminante:** $\Delta = b^2 - 4ac$
> - $\Delta > 0$: dos soluciones reales.
> - $\Delta = 0$: una solución real (raíz doble).
> - $\Delta < 0$: sin solución real.

> [!EXAMPLE]- Actividad 5. Ejercicios con Fórmula General, pág. 145 y 146
> 
> **Ejercicio 1:** $3x^2 + 19x + 20 = 0$
>>[!SUCCESS]- Solución
>> $a=3$, $b=19$, $c=20$
>> $$ \begin{aligned}
>> x &= \frac{-19 \pm \sqrt{19^2 - 4(3)(20)}}{2(3)} \\
>> x &= \frac{-19 \pm \sqrt{361 - 240}}{6} \\
>> x &= \frac{-19 \pm \sqrt{121}}{6} = \frac{-19 \pm 11}{6} \\
>> x_1 &= \frac{-8}{6} = -\frac{4}{3}, \quad x_2 = \frac{-30}{6} = -5
>> \end{aligned} $$
>
> **Ejercicio 2:** $7x^2 - 26x - 8 = 0$
>>[!SUCCESS]- Solución
>> $a=7$, $b=-26$, $c=-8$
>> $$ \begin{aligned}
>> x &= \frac{26 \pm \sqrt{(-26)^2 - 4(7)(-8)}}{14} \\
>> x &= \frac{26 \pm \sqrt{676 + 224}}{14} \\
>> x &= \frac{26 \pm \sqrt{900}}{14} = \frac{26 \pm 30}{14} \\
>> x_1 &= \frac{56}{14} = 4, \quad x_2 = \frac{-4}{14} = -\frac{2}{7}
>> \end{aligned} $$
>
> **Ejercicio 3:** $-4x^2 + 11x + 20 = 0$
>>[!SUCCESS]- Solución
>> Multiplicamos por $-1$: $4x^2 - 11x - 20 = 0$
>> $a=4$, $b=-11$, $c=-20$
>> $$ \begin{aligned}
>> x &= \frac{11 \pm \sqrt{(-11)^2 - 4(4)(-20)}}{8} \\
>> x &= \frac{11 \pm \sqrt{121 + 320}}{8} \\
>> x &= \frac{11 \pm \sqrt{441}}{8} = \frac{11 \pm 21}{8} \\
>> x_1 &= \frac{32}{8} = 4, \quad x_2 = \frac{-10}{8} = -\frac{5}{4}
>> \end{aligned} $$
>
> **Ejercicio 4:** $-5x^2 + 13x + 6 = 0$
>>[!SUCCESS]- Solución
>> Multiplicamos por $-1$: $5x^2 - 13x - 6 = 0$
>> $a=5$, $b=-13$, $c=-6$
>> $$ \begin{aligned}
>> x &= \frac{13 \pm \sqrt{169 - 4(5)(-6)}}{10} \\
>> x &= \frac{13 \pm \sqrt{169 + 120}}{10} \\
>> x &= \frac{13 \pm \sqrt{289}}{10} = \frac{13 \pm 17}{10} \\
>> x_1 &= \frac{30}{10} = 3, \quad x_2 = \frac{-4}{10} = -\frac{2}{5}
>> \end{aligned} $$
>
> **Ejercicio 5:** $3x^2 + 4x - 4 = 0$
>>[!SUCCESS]- Solución
>> $a=3$, $b=4$, $c=-4$
>> $$ \begin{aligned}
>> x &= \frac{-4 \pm \sqrt{16 - 4(3)(-4)}}{6} \\
>> x &= \frac{-4 \pm \sqrt{16 + 48}}{6} \\
>> x &= \frac{-4 \pm \sqrt{64}}{6} = \frac{-4 \pm 8}{6} \\
>> x_1 &= \frac{4}{6} = \frac{2}{3}, \quad x_2 = \frac{-12}{6} = -2
>> \end{aligned} $$
>
> **Ejercicio 6:** $-2x^2 + 11x - 15 = 0$
>>[!SUCCESS]- Solución
>> Multiplicamos por $-1$: $2x^2 - 11x + 15 = 0$
>> $a=2$, $b=-11$, $c=15$
>> $$ \begin{aligned}
>> x &= \frac{11 \pm \sqrt{121 - 4(2)(15)}}{4} \\
>> x &= \frac{11 \pm \sqrt{121 - 120}}{4} \\
>> x &= \frac{11 \pm \sqrt{1}}{4} = \frac{11 \pm 1}{4} \\
>> x_1 &= \frac{12}{4} = 3, \quad x_2 = \frac{10}{4} = \frac{5}{2}
>> \end{aligned} $$
>
> **Ejercicio 7:** $x^2 - 10x + 21 = 0$
>>[!SUCCESS]- Solución
>> $a=1$, $b=-10$, $c=21$
>> $$ \begin{aligned}
>> x &= \frac{10 \pm \sqrt{100 - 84}}{2} \\
>> x &= \frac{10 \pm \sqrt{16}}{2} = \frac{10 \pm 4}{2} \\
>> x_1 &= \frac{14}{2} = 7, \quad x_2 = \frac{6}{2} = 3
>> \end{aligned} $$
>
> **Ejercicio 8:** $-x^2 + 5x + 36 = 0$
>>[!SUCCESS]- Solución
>> Multiplicamos por $-1$: $x^2 - 5x - 36 = 0$
>> $a=1$, $b=-5$, $c=-36$
>> $$ \begin{aligned}
>> x &= \frac{5 \pm \sqrt{25 - 4(1)(-36)}}{2} \\
>> x &= \frac{5 \pm \sqrt{25 + 144}}{2} \\
>> x &= \frac{5 \pm \sqrt{169}}{2} = \frac{5 \pm 13}{2} \\
>> x_1 &= \frac{18}{2} = 9, \quad x_2 = \frac{-8}{2} = -4
>> \end{aligned} $$
>
> **Ejercicio 9:** $x^2 - 8x + 5 = 0$
>>[!SUCCESS]- Solución
>> $a=1$, $b=-8$, $c=5$
>> $$ \begin{aligned}
>> x &= \frac{8 \pm \sqrt{64 - 4(1)(5)}}{2} \\
>> x &= \frac{8 \pm \sqrt{64 - 20}}{2} \\
>> x &= \frac{8 \pm \sqrt{44}}{2} \\
>> x &= \frac{8 \pm 2\sqrt{11}}{2} = 4 \pm \sqrt{11} \\
>> x_1 &= 4 + \sqrt{11}, \quad x_2 = 4 - \sqrt{11}
>> \end{aligned} $$
>
> **Ejercicio 10:** $x^2 - 4x + 8 = 0$
>>[!SUCCESS]- Solución
>> $a=1$, $b=-4$, $c=8$
>> $$ \begin{aligned}
>> x &= \frac{4 \pm \sqrt{(-4)^2 - 4(1)(8)}}{2} \\
>> x &= \frac{4 \pm \sqrt{16 - 32}}{2} \\
>> x &= \frac{4 \pm \sqrt{-16}}{2}
>> \end{aligned} $$
>> Como el discriminante es negativo ($\Delta = -16$), **la ecuación no tiene soluciones reales**.

## Apéndice: Diferencia entre Ecuación Cuadrática y Función Cuadrática

> [!info]+ Contexto
> Es muy común confundir ambos conceptos porque comparten la misma estructura algebraica, pero su propósito y representación geométrica son diferentes.

> [!note]- ¿Qué es la Ecuación Cuadrática?
> Se escribe como:
> $$ax^2 + bx + c = 0$$
> - **Propósito:** Encontrar los valores específicos de $x$ que hacen que la igualdad sea verdadera. A estos valores se les llama **raíces o soluciones**.
> - **Representación:** A nivel gráfico, las soluciones representan los **puntos de corte con el eje $x$** (abscisas) de la parábola.

> [!note]- ¿Qué es la Función Cuadrática?
> Se escribe como:
> $$y = ax^2 + bx + c \quad \text{o} \quad f(x) = ax^2 + bx + c$$
> - **Propósito:** Establecer una **relación de dependencia** entre dos variables. Para cada valor que le asignes a $x$ (variable independiente), obtendrás un único valor de $y$ (variable dependiente). No se iguala a cero, sino que se calcula el resultado.
> - **Representación:** Al graficar todos los pares ordenados $(x, y)$ que cumplen la regla, se obtiene una curva continua en forma de "U" llamada **parábola**.

> [!important]+ Elementos clave de la Función Cuadrática (Parábola)
> Siendo $y = ax^2 + bx + c$, la gráfica presenta:
> 1. **Vértice:** Es el punto más alto o más bajo de la parábola (su punto de inflexión).
> 2. **Eje de simetría:** Es una línea vertical imaginaria que divide la parábola en dos mitades exactamente iguales.
> 3. **Intersección con el eje $y$:** Ocurre cuando $x = 0$, por lo que la gráfica siempre corta al eje vertical en el punto $(0, c)$.
> 4. **Intersección con el eje $x$ (Raíces):** Es aquí donde la función se conecta con la ecuación. Si hacemos $y = 0$, la función se convierte en la ecuación cuadrática $ax^2 + bx + c = 0$. 
>    - Si la parábola corta el eje $x$ en dos puntos, hay dos soluciones.
>    - Si solo lo toca en el vértice, hay una solución (raíz doble).
>    - Si no lo toca, no hay soluciones reales.

> [!example]- Ejemplo comparativo
> **Función:** $y = x^2 - 4$
> Esta es una parábola que abre hacia arriba (porque $a > 0$) y su vértice está en $(0, -4)$.
> 
> **Ecuación:** $x^2 - 4 = 0$
> Si queremos saber exactamente en qué puntos la parábola anterior toca el eje $x$, igualamos la función a cero y resolvemos:
> $$x^2 = 4 \implies |x| = 2 \implies x_1 = 2, x_2 = -2$$
> Por lo tanto, la parábola pasa por los puntos $(-2, 0)$ y $(2, 0)$.