# Diplomado en Técnicas Estadísticas — Módulo II

Entrega final del Módulo II. Aquí dejo los tres notebooks que trabajé a lo largo
del módulo, cada uno sobre un bloque distinto del temario: el espacio de
probabilidad, las variables aleatorias y la estadística inferencial.

La idea de cada notebook fue no quedarme solo en la fórmula, sino apoyar la
teoría con simulaciones en Python para "ver" lo que dicen los resultados
(convergencias, formas de las distribuciones, comportamiento de los estimadores,
etc.).

**Autor:** Cristopher Carlos García

---

## Contenido

### 1. `NB1_Espacio_Probabilidad.ipynb`
Los cimientos: espacio muestral, eventos y axiomas de Kolmogorov. Después paso a
los tres enfoques para asignar probabilidades y los comparo con simulación:

- Enfoque clásico (suma de dos dados, baraja de 52 cartas).
- Enfoque frecuentista (lanzamientos de moneda y su frecuencia relativa).
- Enfoque geométrico (estimación de π con Monte Carlo y el problema del encuentro).

Cierro con el volado como ejemplo de la Ley de los Grandes Números y un ejercicio
propio de urnas.

### 2. `NB2_Variables_Aleatorias.ipynb`
El más extenso. Recorro las distribuciones discretas (uniforme, Bernoulli,
binomial, geométrica, Poisson, binomial negativa e hipergeométrica) y las
continuas (uniforme, normal, exponencial y gamma), siempre con su función,
esperanza, varianza y gráfica. Además:

- Simulación por transformada inversa (incluyendo la distribución de Cauchy).
- Función generadora de momentos y función característica, con cálculo simbólico.
- Ley de los Grandes Números y Teorema Central del Límite con simulaciones.

### 3. `NB3_Estadistica_Inferencial.ipynb`
Cómo pasar de la muestra a conclusiones sobre la población:

- Estimadores puntuales: método de momentos y máxima verosimilitud.
- Propiedades: insesgadez, consistencia y eficiencia (todas verificadas con
  simulación).
- Intervalos de confianza para la media (σ conocida y desconocida) y para una
  proporción, más una visualización de la cobertura real de los intervalos.

---

## Cómo ejecutarlos

Los notebooks corren de arriba a abajo sin errores. Solo hacen falta las
librerías habituales:

```bash
pip install numpy matplotlib scipy sympy
jupyter notebook
```

## Bibliografía

- Rincón, L. *Curso intermedio de probabilidad.*
- Ross, S. *A First Course in Probability.*
- Mood, A., Graybill, F. y Boes, D. *Introduction to the Theory of Statistics.*
- Mendenhall, W. *Introducción a la probabilidad y estadística.*
