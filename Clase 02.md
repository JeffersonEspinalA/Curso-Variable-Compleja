# Fundamentos y Geometría de los Números Complejos
Esta clase consiste en definir qué es un número complejo, cómo se opera con ellos y de qué manera podemos visualizarlos y delimitar regiones dentro del plano complejo. 
Comienza con un repaso de la jerarquía numérica (Naturales, Enteros, Racionales e Irracionales) hasta llegar a los **Reales**. Se introduce la necesidad de los números complejos para resolver ecuaciones que no tienen solución en los reales, como $x^2 + 1 = 0$, lo que da origen a la **unidad imaginaria $i = \sqrt{-1}$**.
Como definición, un número complejo se expresa como $z = a + bi$, donde $a$ es la parte real y $b$ la parte imaginaria.

## Representación y Geometría
A diferencia de los números reales, que se ubican en una línea, los complejos se representan en el **Plano Complejo o de Argand**.
*   **Números Vectoriales:** Los complejos se consideran vectores que van desde el origen $(0,0)$ hasta el punto $(a,b)$.
*   **Ejes:** El eje horizontal es el **Eje Real** y el vertical es el **Eje Imaginario**.

## Operaciones Aritméticas Fundamentales
Se establecen las reglas básicas para manipular estos números:
*   **Suma:** Se suman las partes reales entre sí y las imaginarias entre sí: $(a+c) + (b+d)i$.
*   **Multiplicación:** Se aplica la propiedad distributiva considerando que $i^2 = -1$. La fórmula resultante es $(ac - bd) + (ad + bc)i$.
*   **Inverso Multiplicativo:** Permite realizar la división y se calcula mediante la fórmula $x = \frac{a}{a^2+b^2}$ y $y = \frac{-b}{a^2+b^2}$.

## Conjugado y Módulo
Conceptos esenciales para medir distancias y simplificar expresiones:
*   **Conjugado ($\bar{z}$):** Si $z = a + bi$, su conjugado es $\bar{z} = a - bi$ (un reflejo respecto al eje real).
*   **Módulo ($|z|$):** Representa la longitud del vector y se calcula como $|z| = \sqrt{a^2 + b^2}$.
*   **Propiedad fundamental:** El producto de un número por su conjugado es igual al cuadrado de su módulo ($z \cdot \bar{z} = |z|^2$).

## Formas Polar, Exponencial y Potenciación
Para facilitar cálculos avanzados, el número complejo se puede expresar mediante su magnitud ($r$) y su ángulo ($\theta$):
*   **Forma Polar:** $z = r(\cos \theta + i \sin \theta)$, donde $r$ es el módulo y $\theta = \tan^{-1}(b/a)$.
*   **Forma Exponencial:** $z = re^{i\theta}$.
*   **Teorema de De Moivre:** Permite elevar un complejo a una potencia $n$ fácilmente: $z^n = r^n(\cos(n\theta) + i \sin(n\theta))$.
*   **Radicación:** Un número complejo tiene exactamente $n$ raíces distintas, distribuidas simétricamente en el plano, calculadas con la fase $\phi = \frac{\theta + 2k\pi}{n}$.

## Topología: Regiones en el Plano Complejo
Se introducen conceptos para definir conjuntos de puntos, fundamentales para el estudio de límites:
*   **Vecindad (Disco):** $|z - z_0| < r$ define los puntos dentro de un círculo.
*   **Anillo:** $r_1 < |z - z_0| < r_2$ define los puntos entre dos círculos concéntricos.
*   **Región Cerrada:** Aquella que incluye sus fronteras (usando el símbolo $\leq$).

La clase concluye evaluando funciones $f(z)$ y separándolas en sus componentes real $u(x,y)$ e imaginaria $v(x,y)$. Por ejemplo, para la función exponencial $e^z$, se determina que $u = e^x \cos y$ y $v = e^x \sin y$.
