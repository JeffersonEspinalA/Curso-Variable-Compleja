# Teoremas de Cauchy y Fórmulas Integrales
En esta clase se exploran las consecuencias de la analiticidad en la integración, estableciendo cómo el valor de una función en un punto puede estar determinado enteramente por su comportamiento en un contorno que lo rodea.

## Acotación de Integrales: La Desigualdad ML
Se introduce una herramienta para estimar el tamaño de una integral sin necesidad de resolverla completamente.
*   **Teorema:** Si una función $f$ es continua sobre una curva suave $C$ de longitud $L$, y el módulo de la función está acotado por $M$ ($|f(z)| \leq M$), entonces el módulo de la integral cumple que:
    $$|\int_C f(z) dz| \leq ML$$.

## Dominios Simples y Múltiplemente Conexos
La estructura del dominio donde se integra es crucial para la validez de los teoremas de Cauchy.
*   **Dominio Simplemente Conexo:** Es aquel donde cualquier contorno cerrado puede reducirse a un punto sin salir del dominio (no tiene "hoyos").
*   **Dominio Múltiplemente Conexo:** Contiene uno o más "hoyos" o regiones donde la función no es analítica.

## Teorema de Cauchy-Goursat
Es el pilar de la integración compleja.
*   **Enunciado:** Si una función $f$ es analítica en un dominio simplemente conexo $D$, entonces para cualquier contorno cerrado simple $C$ dentro de $D$, la integral es cero:
    $$\oint_C f(z) dz = 0$$.
*   Esto implica que si una función es entera (analítica en todo el plano), su integral sobre cualquier círculo o elipse siempre será cero.

## Independencia de Trayectoria y Antiderivadas
*   **Independencia de Trayectoria:** En un dominio simplemente conexo, el valor de la integral entre dos puntos $z_0$ y $z_1$ es el mismo, sin importar el camino que se tome.
*   **Teorema Fundamental del Cálculo para Contornos:** Si $f$ es continua y posee una antiderivada $F$ ($F'(z) = f(z)$), entonces la integral se evalúa simplemente restando los valores de la antiderivada en los extremos:
    $$\int_{z_0}^{z_1} f(z) dz = F(z_1) - F(z_0)$$.

## Fórmulas Integrales de Cauchy
Estas fórmulas permiten calcular el valor de una función (o sus derivadas) en un punto interior mediante una integral de contorno.
*   **Para la función:** $f(z_0) = \frac{1}{2\pi i} \oint_C \frac{f(z)}{z - z_0} dz$.
*   **Para las derivadas:** Se extiende a la n-ésima derivada, permitiendo calcular derivadas de cualquier orden mediante integración:
    $$f^{(n)}(z_0) = \frac{n!}{2\pi i} \oint_C \frac{f(z)}{(z - z_0)^{n+1}} dz$$.

## Teoremas de Liouville y Fundamental del Álgebra
Como consecuencias finales de la analiticidad, se presentan resultados de gran alcance:
*   **Teorema de Liouville:** Las únicas funciones enteras (analíticas en todo el plano) que están acotadas son las constantes.
*   **Teorema Fundamental del Álgebra:** Se demuestra, mediante técnicas de variable compleja, que todo polinomio no constante tiene al menos una raíz compleja.
