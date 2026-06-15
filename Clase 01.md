# Funciones Complejas, Mapeos y Límites
En esta sesión se entenderá que ya no se trabajará sobre una sola línea numérica, sino en un plano donde las funciones no se grafican de forma tradicional, sino que se **mapean**.
## El Concepto de Mapeo (Transformación)
Las funciones complejas no se grafican en un espacio cartesiano común porque se necesitaría 4 dimensiones: 2 para los valores de entrada y 2 para los de salida. Por lo tanto, se utiliza el concepto de **Mapeo o Transformación**:
* Plano $z$: Es el plano donde vive la variable independiente o punto original, definido como $z = x + iy$.
* Plano $w$: Es el plano de destino donde vive el resultado de aplicar la función, definido como $w = f(z) = u + iv$.

**Visualización**: Una función compleja actúa como una instrucción geométrica que toma el plano $z$, lo deforma, lo estira o lo desplaza, y lo plasma en el plano $w$.

## Transformaciones Geométricas Elementales
Las funciones complejas simples actúan como transformaciones geométricas sobre los puntos del plano:
* **Traslación** ($T(z) = z + b$): Desplaza cada punto $z$ por un vector constante $b$.
* **Rotación** ($R(z) = e^{i\theta}z$): Gira los puntos alrededor del origen un ángulo $\theta$. Para que sea una rotación pura, el módulo del multiplicador debe ser $|a|=1$.
* **Ampliación o Dilatación** ($M(z) = az$): Si $a > 0$ es un número real, la función agranda o achica la figura original.

## Curvas Paramétricas y Funciones Inversas
* **Curvas paramétricas**: Se definen mediante funciones de variable real $t$, de la forma $z(t) = x(t) + iy(t)$, donde los puntos forman una trayectoria en el plano complejo.
* **Funciones Inversas** ($f^{-1}$): Si una función es unívoca (asocia un solo valor de salida a cada entrada), su inversa deshace el mapeo, cumpliendo que $f^{-1}(z) = w$ si $f(w) = z$.

## Límites en el Plano Complejo
El límite de una función $f(z)$ cuando $z$ tiende a $z_0$ es el valor $L$ al que se aproximan las imágenes.
* Definición formal: Se utiliza el criterio $\epsilon-\delta$, que asegura que $f(z)$ está tan cerca de $L$ como se desee, siempre que $z$ esté suficientemente cerca de $z_0$.
* Criterio de no existencia: Para que un límite exista, debe ser el mismo sin importar la trayectoria por la que nos acerquemos a $z_0$. Si al acercarnos por dos caminos distintos obtenemos valores diferentes, el límite no existe.
* Cálculo práctico: Se puede calcular el límite separando la función en sus partes real $u(x,y)$ e imaginaria $v(x,y)$.

## Continuidad
Una función compleja $f$ es continua en un punto $z_0$ si se cumplen tres condiciones:
1. $f(z_0)$ está definida.
2. El límite de $f(z)$ cuando $z \to z_0$ existe.
3. **El valor del límite es igual al valor de la función**: $\lim_{z \to z_0} f(z) = f(z_0)$.
