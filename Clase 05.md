# Integración en el Plano Complejo
Esta clase establece las bases del cálculo integral para variables complejas, definiendo los tipos de curvas y la metodología para evaluar integrales de contorno.

## Funciones Inversas Hiperbólicas
Antes de entrar de lleno en la integración, se concluye el tema de funciones elementales:
*   **Definición:** Las inversas (como $sinh^{-1} z$ o $cosh^{-1} z$) se definen mediante logaritmos complejos y raíces cuadradas.
*   **Naturaleza Multívoca:** Al depender de logaritmos y raíces, estas funciones poseen múltiples valores, por lo que es necesario establecer **ramas y valores principales** para su evaluación.

## Concepto de Integral Definida y Sumas de Riemann
Se introduce la integral compleja como una extensión de la real, utilizando el proceso de **sumas de Riemann**:
*   Se divide el intervalo de integración en $n$ subintervalos.
*   La función debe estar definida y ser continua en los puntos del intervalo para garantizar su integrabilidad.
*   La integral se visualiza como la suma de los productos de la función por los pequeños desplazamientos ($\Delta z$) a lo largo de la trayectoria.

## Terminología de Curvas y Contornos
Para integrar correctamente, es fundamental clasificar el camino (trayectoria):
*   **Curva Suave:** Una curva cuyas derivadas de sus componentes son continuas y no se anulan simultáneamente.
*   **Curva Suave por Tramos:** Formada por una unión finita de curvas suaves.
*   **Curva Simple:** No se cruza a sí misma, excepto posiblemente en sus extremos.
*   **Curva Cerrada:** Aquella donde el punto inicial y el final coinciden (como un círculo o elipse).
*   **Contorno:** En variable compleja, se suele usar este término para referirse a las trayectorias o caminos de integración.

## Integrales de Línea y Parametrización
La evaluación práctica de una integral depende de la **parametrización** de la curva $z(t) = x(t) + iy(t)$:
*   **Fórmula Fundamental:** Para evaluar la integral de $f(z)$ sobre un contorno $C$, se utiliza la relación:
    $$\int_C f(z) dz = \int_a^b f(z(t)) z'(t) dt$$
    donde $z'(t)$ es la derivada de la trayectoria.
*   **Independencia y Segmentación:** Si una trayectoria es suave por tramos, la integral total es la **suma de las integrales** calculadas sobre cada segmento individual.

## Propiedades y Orientación
*   **Orientación:** El signo de la integral depende del sentido del recorrido. Se considera **orientación positiva** aquella que va en contra de las manecillas del reloj.
*   **Cambio de Sentido:** Si se invierte la dirección de la trayectoria, el valor de la integral cambia de signo.
*   **Integrales Cerradas:** Se demuestra que la integral de ciertas funciones sobre curvas cerradas (como un círculo) puede resultar en cero bajo condiciones de analiticidad, aunque no siempre es el caso.

## Resultados Clave de la Clase
*   Se evalúan integrales sobre círculos y parábolas utilizando sustituciones trigonométricas y algebraicas.
*   Un resultado fundamental presentado es que la integral de la función $1/z$ a lo largo de una circunferencia unitaria es igual a $2\pi i$.
