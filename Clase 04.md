# Potencias, Funciones Trigonométricas e Inversas
En esta clase se aborda la definición y el comportamiento de las funciones elementales en el plano complejo, donde conceptos como la potenciación y la trigonometría adquieren propiedades únicas debido a la presencia de la unidad imaginaria.

## Potencias Complejas
Las potencias se definen a partir de la función exponencial y el logaritmo complejo.
*   **Definición:** Para un número complejo $\alpha$ y $z \neq 0$, la potencia se define como $z^\alpha = e^{\alpha \ln z}$.
*   **Multivaluación:** Debido a que el logaritmo tiene infinitos valores (por el argumento $\theta + 2k\pi$), una potencia compleja generalmente tiene **múltiples resultados**.
*   **Valor Principal:** Para obtener un único resultado, se utiliza el **valor principal de la potencia**, restringiendo el logaritmo a su rama principal.

## Derivación de Potencias
*   Una rama de la potencia $z^\alpha$ es analítica en el dominio donde el logaritmo es continuo (evitando el corte de rama).
*   **Regla de la potencia:** La derivada cumple con la fórmula clásica: $\frac{d}{dz} z^\alpha = \alpha z^{\alpha-1}$, siempre que se trabaje dentro de una rama específica.

## Funciones Trigonométricas Complejas
A diferencia de las funciones reales, el seno y el coseno complejos se definen mediante la **fórmula de Euler**:
*   **Seno:** $\sin z = \frac{e^{iz} - e^{-iz}}{2i}$.
*   **Coseno:** $\cos z = \frac{e^{iz} + e^{-iz}}{2}$.
*   **Propiedades:**
    *   Son funciones **periódicas** con periodo $2\pi$.
    *   **Módulos:** A diferencia de los reales, los módulos de $\sin z$ y $\cos z$ pueden ser mayores a 1. Por ejemplo, $|\sin z| = \sqrt{\sin^2 x + \sinh^2 y}$.
    *   **Ceros:** Los ceros de $\sin z$ ocurren solo en múltiplos reales de $\pi$ ($z = n\pi$).

## Funciones Hiperbólicas
Se definen de forma análoga a las trigonométricas pero sin la unidad imaginaria en el exponente:
*   **Seno hiperbólico:** $\sinh z = \frac{e^z - e^{-z}}{2}$.
*   **Coseno hiperbólico:** $\cosh z = \frac{e^z + e^{-z}}{2}$.
*   Existe una relación directa entre ambas: por ejemplo, $\sin(iz) = i \sinh z$ y $\cos(iz) = \cosh z$.

## Funciones Inversas (Trigonométricas e Hiperbólicas)
Las funciones como el arcoseno ($\arcsin z$) o el arcocoseno ($\arccos z$) se expresan en términos de **logaritmos complejos**.
*   **Ejemplo:** El $\arcsin z = -i \ln(iz + \sqrt{1 - z^2})$.
*   Al ser definidas mediante logaritmos y raíces cuadradas, estas funciones son **multivaluadas** y requieren la elección de una rama para su análisis.
