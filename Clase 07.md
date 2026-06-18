# Teoremas Avanzados, Series y Singularidades

En esta clase se exploran criterios adicionales de analiticidad, el comportamiento de las sucesiones y series en el plano complejo, y cómo representar funciones mediante potencias de $z$.

## Teoremas de Morera y del Módulo Máximo
*   **Teorema de Morera:** Funciona como el inverso del Teorema de Cauchy. Establece que si una función es continua en un dominio simplemente conexo y su integral sobre cualquier contorno cerrado es cero, entonces la función debe ser analítica en ese dominio.
*   **Teorema del Módulo Máximo:** Si una función $f$ es analítica y no constante en una región cerrada y acotada $R$, el valor máximo de su módulo $|f(z)|$ ocurre siempre en la frontera del dominio y nunca en su interior.

## Sucesiones y Series Complejas
*   **Sucesión:** Es una función que asigna un número complejo a cada entero positivo. Se dice que es **convergente** si su límite existe cuando $n$ tiende al infinito.
*   **Series:** Una serie infinita converge si la sucesión de sus **sumas parciales** tiene un límite finito.
*   **Series Geométricas:** Tienen la forma $\sum \alpha z^{k-1}$. Estas series convergen al valor $\frac{\alpha}{1-z}$ siempre que el módulo $|z| < 1$.
*   **Criterios de Convergencia:** Para determinar si una serie converge, se utilizan pruebas como la **Prueba de la Razón** (comparando términos consecutivos) y la **Prueba de la Raíz**. Una condición necesaria para la convergencia es que el límite del término $n$-ésimo sea cero.

## Series de Potencias: Taylor y Maclaurin
*   **Series de Potencias:** Son sumas centradas en un punto $z_0$ de la forma $\sum \alpha_k (z - z_0)^k$. Dentro de su círculo de convergencia, estas series pueden derivarse e integrarse término a término.
*   **Serie de Taylor:** Permite representar cualquier función analítica como una serie de potencias centrada en $z_0$.
*   **Serie de Maclaurin:** Es simplemente una serie de Taylor centrada en el origen ($z_0 = 0$).

## Series de Laurent
Cuando una función no es analítica en un punto (singularidad), se utiliza la **Serie de Laurent**. Esta serie es válida en dominios anulares (anillos) y se caracteriza por tener potencias tanto positivas como **negativas** de $(z - z_0)$. La parte de la serie con potencias negativas se conoce como la **parte principal**.

## Clasificación de Singularidades Aisladas
Un punto $z_0$ es una singularidad aislada si la función no es analítica allí, pero sí lo es en su vecindad cercana. Según su serie de Laurent, se clasifican en:
*   **Singularidad Removible:** La parte principal de la serie es cero.
*   **Polo de orden $n$:** La parte principal tiene un número finito de términos (hasta la potencia $-n$). Si $n=1$, se llama **polo simple**.
*   **Singularidad Esencial:** La parte principal contiene infinitos términos con potencias negativas.
