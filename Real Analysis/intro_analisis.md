# Números reales:

Axiomas de los números reales:

Un conjunto no vacío $\mathbb{R}$ junto que tiene operaciones $+$, $\cdot$ y un orden $\leq$ es le llamamos los números reales si satisface:

1. $(\mathbb{R},+,0)$ es un grupo abeliano
2. $(\mathbb{R} \setminus { 0}, \cdot, 1)$ es un grupo abeliano $1 \neq 0$
3. Ley distributiva: $x(y+z) = xy + xz$
4. $\leq$ es un orden total, compatible con $+$ y $\cdot$, y tiene la propiedad arquimediana
5. Toda sucesión de Cauchy es convergente
6. Axioma de completez
7. Propiesdad de intervalos anidados


Va ser muy importante que podamos medir distancias para poder hacer análisis. De aquí vendra la definición de límites y de derivadas. En $\mathbb{R}$ mediremos distancias con una función que llamamos valor absoluto:

$$
|x| = \begin{cases}
x, & \text{si } x \geq 0 \\
-x, & \text{si } x < 0
\end{cases}
$$

Propiedades del valor absoluto:
1. Multiplicación de valores absolutos:
 $$|x \cdot y| = |x| \cdot |y|$$
2. Desigualdad del triángulo: 
$$|x + y| \leq |x| + |y|$$



#### Toda sucesión de Cauchy es convergente

Una sucesión $\{a_n\}$ en los números reales es de Cauchy, si para todo número real positivo $\epsilon > 0$ existe un número natural $N$ tal que para todo $m, n \geq N$ se cumple que $|a_m - a_n| < \epsilon$, 

Mostrar que una suceción es de cauchy es una manera de mostrar que converge sin hacer referencia a un límite.

#### Propiedad de intervalos anidados

La propiedad de intervalos anidados es una propiedad de los números reales y establece que si tenemos una sucesión de intervalos cerrados y acotados, donde cada intervalo contiene al siguiente, entonces la intersección de todos estos intervalos es un único punto.

Proposición: si tenemos una sucesión de intervalos cerrados y acotados $[a_1, b_1], [a_2, b_2], [a_3, b_3], \ldots$, donde se cumple que $[a_{n+1}, b_{n+1}] \subseteq [a_n, b_n]$ para todo $n$, entonces la intersección de todos estos intervalos es un único punto, es decir:

$$\bigcap_{n=1}^{\infty} [a_n, b_n] = \{x\}$$



nota: Esta propiedad permite demostrar la existencia de números reales mediante la construcción de sucesiones de intervalos anidados.


#### Propiedad arquimediana

La propiedad arquimediana establece que para cualquier número real positivo $x$, existe un número natural $n$ tal que $n > x$.

En otras palabras, no importa cuán grande sea un número real positivo, siempre podemos encontrar un número natural más grande que él.

#### Axioma de completitud

El axioma de completitud establece que todo conjunto no vacío de números reales acotado superiormente tiene un supremo.

#### Supremo

Sea $A$ un conjunto de números reales que posee una cota superior. Definimos La mínima cota superior de $A$ también llamada supremo de A como el menor número real $s$ que es cota superior de dicho conjunto.


proposición: Sea $A$ una conjunto acotado de números reales, $s = supA$ si y sólo si:

1. $s$ es una cota superior de $A$, es decir, $a \leq s$ para todo $a \in A$.
2. Para cualquier número real $\epsilon > 0$, existe un elemento $a \in A$ tal que $s - \epsilon < a$.

Este axioma  garantiza la existencia de límites, supremos e ínfimos en los conjuntos de números reales.