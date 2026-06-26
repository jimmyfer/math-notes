# Sistemas de Ecuaciones Lineales: Resolución de Incógnitas Acopladas

Un **sistema de ecuaciones lineales** es un conjunto de dos o más ecuaciones de primer grado que comparten las mismas variables. Resolver el sistema implica hallar el valor simultáneo de las incógnitas que satisface todas las ecuaciones al mismo tiempo.

---

## 📊 Interpretación Geométrica y Tipos de Sistemas

En un sistema de dos variables ($x, y$), cada ecuación representa una línea recta en un plano bidimensional. La solución del sistema corresponde analíticamente al punto geométrico de intersección entre dichas rectas.


Dependiendo de cómo se comporten estas rectas, los sistemas se clasifican en:

1. **Sistema Compatible Determinado (SCD):** Las rectas se cortan en un **único punto**. El sistema tiene una solución única.
2. **Sistema Compatible Indeterminado (SCI):** Las rectas son **coincidentes** (la misma línea expresada de forma diferente). El sistema tiene infinitas soluciones.
3. **Sistema Incompatible (SI):** Las rectas son **paralelas** y nunca se cruzan. El sistema no tiene solución.

---

## 🛠️ Métodos Analíticos de Resolución

Para sistemas lineales de dimensiones básicas ($2 \times 2$), existen tres métodos algebraicos tradicionales. Todos se basan en el principio de reducción: transformar un problema de dos variables en una sola ecuación con una variable utilizando las reglas de despeje.

Sea el sistema de prueba para los tres métodos:
$$
\begin{cases}
2x + y = 7 & \text{(Ecuación 1)} \\
x - 3y = -7 & \text{(Ecuación 2)}
\end{cases}
$$

### 1. Método de Sustitución
Consiste en aislar una de las incógnitas en una ecuación y sustituir su expresión en la otra ecuación.

* **Paso 1:** Despejar $y$ en la Ecuación 1:
  $$y = 7 - 2x$$
* **Paso 2:** Sustituir esta expresión en lugar de $y$ en la Ecuación 2:
  $$x - 3(7 - 2x) = -7$$
* **Paso 3:** Resolver la ecuación lineal resultante:
  $$x - 21 + 6x = -7$$
  $$7x - 21 = -7$$
  $$7x = 14 \implies x = 2$$
* **Paso 4:** Sustituir el valor hallado para obtener $y$:
  $$y = 7 - 2(2) \implies y = 3$$

---

### 2. Método de Igualación
Consiste en despejar la misma incógnita en ambas ecuaciones e igualar las expresiones resultantes.

* **Paso 1:** Despejar $x$ en la Ecuación 1 y en la Ecuación 2:
  $$2x = 7 - y \implies x = \frac{7 - y}{2}$$
  $$x = 3y - 7$$
* **Paso 2:** Igualar ambas expresiones algebraicas:
  $$\frac{7 - y}{2} = 3y - 7$$
* **Paso 3:** Multiplicar toda la ecuación por 2 para eliminar el denominador y despejar $y$:
  $$7 - y = 2(3y - 7)$$
  $$7 - y = 6y - 14$$
  $$21 = 7y \implies y = 3$$
* **Paso 4:** Sustituir el valor de $y$ en cualquiera de las ecuaciones despejadas:
  $$x = 3(3) - 7 \implies x = 2$$

---

### 3. Método de Reducción (Suma y Resta)
Consiste en multiplicar una o ambas ecuaciones por números convenientes para que los coeficientes de una de las incógnitas sean iguales pero de signo contrario, permitiendo eliminarla al sumar las ecuaciones.

* **Paso 1:** Multiplicar la Ecuación 1 por $3$ para igualar el coeficiente de la variable $y$ con signo opuesto al de la Ecuación 2:
  $$3 \cdot (2x + y = 7) \implies 6x + 3y = 21$$
* **Paso 2:** Sumar miembro a miembro la ecuación modificada y la Ecuación 2:
  $$
  \begin{array}{rcc}
    6x + 3y &=& 21 \\
  +\quad x - 3y &=& -7 \\
  \hline
    7x + 0 &=& 14
  \end{array}
  $$
* **Paso 3:** Resolver la ecuación directa resultante:
  $$7x = 14 \implies x = 2$$
* **Paso 4:** Sustituir el valor numérico en la Ecuación 1 original:
  $$2(2) + y = 7 \implies 4 + y = 7 \implies y = 3$$

---

## 🗺️ Línea de Progreso Interna (Álgebra Elemental)
* 📥 [[Álgebra elemental]] *(Cimientos conceptuales básicos)*
* 📥 [[Manipulación y Despeje de Ecuaciones]] *(Reglas de balance algebraico)*
* 📍 **[[Sistemas de Ecuaciones Lineales]]** *(Sesión analítica actual)*

---

## ↩️ Navegación
* Volver al índice temático: [[Fase 1 - Los Cimientos | 📂 Fase 1 - Los Cimientos]]