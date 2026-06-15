# Resumen de la Clase 03: Continuidad, Ramas y Derivación Compleja

Esta sesión es fundamental porque marca la transición del análisis de límites y continuidad hacia la **derivación compleja** y las **funciones analíticas**. Se profundiza en las propiedades de las funciones continuas y se introducen las herramientas clave para el cálculo diferencial en el plano complejo, como las ecuaciones de Cauchy-Riemann.

## Profundización en la Continuidad
*   **Teorema de Componentes:** Una función compleja $f(z) = u(x,y) + iv(x,y)$ es continua en un punto si y solo si sus funciones componentes reales, $u$ y $v$, son continuas en dicho punto.
*   **Propiedades:** Si dos funciones son continuas, también lo son su suma, diferencia, producto y cociente (siempre que el denominador no sea cero).
*   **Continuidad Global:** Las funciones **polinómicas** son continuas en todo el plano complejo, mientras que las **racionales** son continuas en todos los puntos de su dominio.
*   **Funciones Acotadas:** Una función es acotada en una región cerrada $R$ si existe una constante $M > 0$ tal que $|f(z)| \leq M$ para todo $z$ en esa región.

## Funciones Multivaluadas y Ramas
Debido a que operaciones como la radicación generan múltiples resultados, se introducen conceptos para manejarlas como funciones tradicionales:
*   **Rama:** Es una porción de una función multivaluada que se define como unívoca y continua en un dominio específico.
*   **Corte de Rama:** Es una curva que se excluye del dominio para que la función sea continua en el resto del espacio.
*   **Punto de Rama:** Es el punto común a todos los cortes de rama. Su utilidad principal es permitir la segmentación del espacio para elegir un valor específico de una raíz (como una raíz quinta) según convenga.

## La Derivada Compleja
Al igual que en el cálculo real, la derivada $f'(z_0)$ se define mediante el límite de la diferencia: $\lim_{\Delta z \to 0} \frac{f(z_0 + \Delta z) - f(z_0)}{\Delta z}$.
*   **Reglas de Derivación:** Las reglas conocidas para funciones reales (suma, producto, cadena) se aplican de la misma forma en el plano complejo.
*   **Requisito previo:** Para que una función sea derivable, debe ser primero continua, aunque ser continua no garantiza que sea derivable.

## Analiticidad y Regla de L'Hôpital
*   **Función Analítica:** Una función es analítica en un punto si es derivable en ese punto y en todos los puntos de una vecindad cercana.
*   **Función Entera:** Es aquella que es analítica en **todo** el plano complejo, como los polinomios.
*   **Puntos Singulares:** Son aquellos puntos específicos donde una función deja de ser analítica.
*   **Regla de L'Hôpital:** Se puede aplicar para resolver indeterminaciones del tipo $0/0$ en funciones analíticas, derivando el numerador y el denominador por separado.

## Ecuaciones de Cauchy-Riemann
Es el criterio principal para verificar si una función compleja es derivable. Si $f(z) = u + iv$, deben cumplirse las siguientes igualdades de derivadas parciales:
1.  $\frac{\partial u}{\partial x} = \frac{\partial v}{\partial y}$
2.  $\frac{\partial u}{\partial y} = -\frac{\partial v}{\partial x}$

## Funciones Armónicas
Una función real $\phi(x,y)$ es armónica si posee derivadas parciales de primer y segundo orden continuas y satisface la **ecuación de Laplace**: $\frac{\partial^2 \phi}{\partial x^2} + \frac{\partial^2 \phi}{\partial y^2} = 0$.
Si una función $f(z) = u + iv$ es analítica, entonces $v$ se denomina la conjugada armónica de $u$. Ambas funciones componentes de una función analítica son siempre armónicas.
