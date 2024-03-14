## Sucesiones

Una sucesión de números reales es una función $f: \mathbb{N} \rightarrow \mathbb{R}$ que asigna a cada número natural $n$ un número real $a_n$.

Podemos pensar en una sucesión como una lista ordenada de números reales, algunas notaciones usadas son:


 $$(a_1, a_2, a_3, \ldots) \hspace{5pt}ó\hspace{5pt}
 (a_n)_{n=1}^{\infty} \hspace{5pt} ó \hspace{5pt} (a_n)_{\in \N} \hspace{5pt} ó \hspace{5pt} (a_n)$$ 



ejemplos:

1. $(a_n)_{\in \N} = ((-1)^{n})_{n \in \N} = (-1,1,-1,1,-1,1,\ldots)$
2. $(b_n)_{n \in \N} = (n^2)_{n \in \N} = (1,4,9,16,25,\ldots)$
3. $(c_n)_{n \in \N} = \left(\frac{1}{2^n}\right)_{n \in \N} = \left(1,\frac{1}{2},\frac{1}{4},\frac{1}{8},\ldots\right)$
4. $(d_n)_{n \in \N} = \left(\frac{n}{n+1}\right)_{n \in \N} = \left(\frac{1}{2},\frac{2}{3},\frac{3}{4},\frac{4}{5},\ldots\right)$



#### Suceción Convergente
$ (a_n)_{n \in \mathbb{N}}$ es una sucesión convergente si existe un número real $L$ tal que para todo $\epsilon > 0$, existe un número natural $N$ tal que para todo $n \geq N$, se cumple $|a_n - L| < \epsilon$.

ejemplo.
Demostrar que la sucesión $a_n = \frac{1}{n}$ converge a 0.

Ideas: 
Lee la definición de convergencia de una suceción.

Necesitamos comenzar con un número cualquiera positivo $\epsilon>0$ y sabemos  que al final de nuestra demostración llegarmos a que $|a_n - 0| < \epsilon$

Lo único que falta es ¿Cómo definiremos a la N ? y ún cálculo para mostrar que $|a_n - 0| < \epsilon$.

Demostración:

Dado $\epsilon > 0$, queremos encontrar un número natural $N$ tal que para todo $n \geq N$, se cumpla $|a_n - 0| < \epsilon$.

Escogemos $N \in \N$ tal que $N \cdot \epsilon  \gt 1$. Esto sabemos que lo podemos hacer por la propiedad arquimideana.

Entonces para $n \geq N$, tendremos que 


 $|a_n - 0| = |a_n|= \frac{1}{n} \leq \frac{1}{N} \lt \epsilon$

Por lo tanto, hemos demostrado que la sucesión $a_n = \frac{1}{n}$ converge a 0.

ejemplo.
