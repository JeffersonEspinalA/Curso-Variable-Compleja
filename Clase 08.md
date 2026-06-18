# Teoría de Residuos y Aplicaciones en Integración

En esta clase se introducen los conceptos de ceros y polos de funciones analíticas, se define formalmente el residuo y se presenta el **Teorema del Residuo de Cauchy** como la herramienta definitiva para el cálculo integral.

## Ceros y Polos de Funciones Analíticas
*   **Ceros de orden $n$:** Un punto $z_0$ es un cero de orden $n$ si la función y sus primeras $n-1$ derivadas son cero en ese punto, pero la $n$-ésima derivada es distinta de cero.
    *   **Teorema:** Una función tiene un cero de orden $n$ si y solo si se puede escribir como $f(z) = (z - z_0)^n \phi(z)$, donde $\phi(z)$ es analítica y no nula en $z_0$.
*   **Polos de orden $n$:** Un punto es un polo de orden $n$ si la función se expresa como $f(z) = \frac{\phi(z)}{(z - z_0)^n}$ con $\phi(z_0) \neq 0$.
    *   Si una función es el cociente de dos funciones analíticas, $f(z) = \frac{G(z)}{H(z)}$, y $H$ tiene un cero de orden $n$ mientras $G(z_0) \neq 0$, entonces $f$ tiene un polo de orden $n$ en ese punto.

## El Concepto de Residuo
El residuo de una función en una singularidad aislada $z_0$ es el coeficiente $a_{-1}$ de su serie de Laurent. Se denota como $Res(f, z_0)$. 

Fórmulas de cálculo:
*   **Polo simple:** $Res(f, z_0) = \lim_{z \to z_0} (z - z_0) f(z)$.
*   **Polo de orden $n$:** $Res(f, z_0) = \frac{1}{(n-1)!} \lim_{z \to z_0} \frac{d^{n-1}}{dz^{n-1}} [(z - z_0)^n f(z)]$.

## Teorema del Residuo de Cauchy
Este teorema establece que si una función es analítica dentro y sobre un contorno cerrado simple $C$, excepto en un número finito de singularidades aisladas $z_k$ dentro de $C$, entonces la integral es:
$$\oint_C f(z) dz = 2\pi i \sum_{k=1}^n Res(f, z_k)$$.
*   **Ejemplo práctico:** Al evaluar $\oint \frac{2z+6}{z^2+4} dz$ en un círculo que solo encierra la singularidad $-2i$, se calcula el residuo en ese punto y se multiplica por $2\pi i$ para obtener el resultado de la integral.

## Aplicaciones en Integrales Reales
La teoría de residuos permite resolver integrales de variable real que de otro modo serían muy complejas:
*   **Integrales Trigonométricas:** Integrales de la forma $\int_0^{2\pi} F(\cos \theta, \sin \theta) d\theta$ se resuelven transformándolas en una integral de contorno sobre el círculo unitario mediante la sustitución $z = e^{i\theta}$.
*   **Integrales Impropias:** Se calculan integrales desde $-\infty$ hasta $\infty$ utilizando semicírculos en el plano superior y aplicando el **Valor Principal de Cauchy (VP)**.
*   **Lema de Jordan:** Se utiliza para demostrar que, bajo ciertas condiciones de decaimiento de la función, la integral sobre el arco semicircular tiende a cero cuando el radio tiende al infinito, dejando solo el valor de la integral sobre el eje real.
*   **Contornos con muescas (Indented Contours):** Cuando una función tiene un polo sobre el eje real, se utiliza un pequeño arco de radio $r \to 0$ para "bordear" la singularidad.

## Resultados Notables de la Sesión
*   Se demuestra que la integral de $\int_0^{2\pi} \frac{1}{(2 + \cos \theta)^2} d\theta$ es igual a $\frac{4\pi}{3\sqrt{3}}$.
*   Se evalúan integrales infinitas como $\int_0^\infty \frac{x \sin x}{x^2+9} dx$, obteniendo $\frac{\pi}{2e^3}$ mediante el uso de simetría y residuos.
