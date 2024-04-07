
#materia/matemática/algebra #apuntes-practicas-tareas 

* Es una expresión algebraica que se clasifica de acuerdo con la cantidad de términos (separados por suma o resta) que tiene.
	* Monomio
		* Un solo termino.
			* $2 \cdot y$ 
			* $2x^2 \cdot z$
	* Binomio
		* $x \cdot y + 2x^2 \cdot z$
	* Trinomio
	* etc.
* Entonces podemos decir que el polinomio es la suma o resta de cualquier cantidad de monomios.
* Ejemplo
	* $x^2 + 2x - 1$
* Forma General
	* $P(x) = a_nx^n + a_{n-1}x^{n-1} + a_{n-2}x^{n-2} + ... a_0$
	* Donde x es la variable
	* n (el de las x) son las potencias, y la mas grande marca el grado del polinomio.
		* El grado $n \in \mathbb{N} + {0}$ 
			* n (el exponente) pertenece a los números naturales enteros y el cero.
	* y a son los coeficientes, donde la que esta multiplicada por el exponente mas alto marca cual es el coeficiente principal.
		* El coeficiente principal pertenece a los reales.
	* La a sin x es el termino independiente.
	* Ejemplo.
		* $P(x) = 8x^3 - 2x^2 + x -2$
		* 8 es el coeficiente principal.
		* El polinomio es de grado 3
			* El termino independiente es -2
	* Para que un polinomio exista y sea valido
		* $a_n \neq 0$
			* El coeficiente principal no debe ser cero.
			* El siguiente polinomio es invalido por que una x esta elevada a un numero no natural.
				* $Q(x) = x^4 + 3x^3 + x^{\frac 1 2} - 2$
* Los polinomios puede ser.
	* Completos o incompletos
		* Si están todos los exponentes desde n a 0
	* Ordenados o desordenados, y en forma creciente o decreciente
		* También basado en sus exponentes.
* Operaciones con polinomios
	* En las operaciones con polinomios se llaman términos semejantes a los que tienen la misma potencia en x.
	* Suma
		* Hay que completar y ordenar en forma decreciente los polinomios y luego sumar cada termino con el del otro polinomio.
		* Ej.
			* $P(x) = 3x^3 - 2x + 1$
			* $Q(x) = 4x^4 - 2x^3 +x^2 - 2$
			* Completamos y Ordenamos los polinomios
			* $P(x) = 0x^4 + 3x^3 + 0x^2 -2x +1$
			* $Q(x) = 4x^4 - 2x^3 +x^2 + 0x - 2$
			* Ahora los sumamos
			* $$
\begin{align*}
P(x) &= 0x^4 + 3x^3 + 0x^2 - 2 +1 \\
Q(x) &= 4x^4 -2x^3 + x^2 + 0x - 2 \\
R(x) &= \overline{4x^4 + 5x^3 - x^2 +2x +3}
\end{align*}
$$
	* Diferencia
		* Igual que la suma en cuanto a la forma de proceder.
		* Se recomienda hacer lo siguiente.
			* $P(x) + (-Q(x))$
			* Volver negativo, cambiando el signo de todos los términos del segundo polinomio y sumar. (El profesor dijo que es mas seguro de esta manera)
			* Al final del día la resta es lo mismo que sumar el negativo de otro numero. (no se si esta bien expresado pero me entiendo.)
		* Ej.
			* Tomando los polinomios del ejemplo de la adición.
			* Damos vuelta Q(x).
				* $-Q(x) = $-4x^4 + 2x^3 - x^2 + 0x +2$
			* Restamos (en este caso sumamos al contrario de Q)
				* $$
\begin{align*}
P(x) &= 0x^4 + 3x^3 + 0x^2 - 2 +1 \\
Q(x) &= -4x^4 + 2x^3 - x^2 + 0x + 2 \\
R(x) &= \overline{-4x^4 + 5x^3 - x^2 - 2x + 3}
\end{align*}
$$
	* Multiplicación
		* Se realiza la operación distributiva entre dos polinomios.
		* Generalmente queda un chorizo largo de números pero que después podemos reducir mediante cancelación y sumas y restas de términos semejantes.
		* Ej.
			* $P(x) = x^3 + 2x^2 - x +1$
			* $Q(x) = x^2 - 2x +2$
			* Si hacemos la distributiva queda lo siguiente.
			* $x^5 - 2x^4 + 2x^3 + 2x^4 -4x^3 + 4x^2 - x^3 + 2x^2 - 2x + x^2 -2x + 2$
			* Cancelamos por ej ($\cancel{-2x^4} \cancel{+2x^4}$) y sumamos y restamos términos semejantes (misma elevación en la x).
			* El resultado es.
				* $x^5 - 3x^3 +7x^2 -4x +2$
	* División
		* Es la única operación que generalmente arroja dos polinomios como resultado, cociente y resto.
		* Hay dos reglas importantes para que se pueda dividir un polinomio.
			* $Q(x) \neq 0$
			* El grado de Q(x) <= grado de P(x)
		* Para ver en mas detalle esta operación en particular que es difícil de dibujar con `mathjax` ver el documento.
			* [[Ej.polinomios.pdf]]