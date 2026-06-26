# 📍 Límites — Introducción Intuitiva

## 🧠 El Demonio del $0/0$
En aritmética elemental, dividir entre cero está prohibido. Cuando modelamos sistemas en movimiento (como la velocidad instantánea de una moto), la matemática estática nos devuelve una indeterminación: $\frac{0}{0}$.

El cálculo no intenta calcular qué pasa *en* el punto prohibido, sino qué pasa **infinitamente cerca** de él.

## 🛠️ Experimento Numérico 1
Analizamos el comportamiento de la función:
$$f(x) = \frac{x^2 - 1}{x - 1}$$

*   **Evaluación directa ($x = 1$):** $f(1) = \frac{1^2 - 1}{1 - 1} = \frac{0}{0}$ (Indeterminación)
* **Aproximación por la izquierda ($x < 1$):** Si evaluamos valores como $x = 0.999$, la función nos devuelve $f(0.999) = 1.999$. A medida que nos acercamos a $1$ por valores menores, el resultado tiende a **$2$**.
* **Aproximación por la derecha ($x > 1$):** Si evaluamos valores como $x = 1.001$, la función nos devuelve $f(1.001) = 2.001$. A medida que nos acercamos a $1$ por valores mayores, el resultado tiende a **$2$**.

## 💡 Conclusión:
Aunque evaluar la función directamente en $x = 1$ provoca un colapso matemático ($\frac{0}{0}$), analizar el comportamiento a su alrededor demuestra que la función tiende con total precisión al valor de **$2$**. 

Por lo tanto, el **límite existe** y se escribe formalmente así:
$$\lim_{x \to 1} \frac{x^2 - 1}{x - 1} = 2$$