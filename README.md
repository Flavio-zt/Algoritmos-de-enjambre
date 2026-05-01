# Algoritmos-de-enjambre
# 🧠 Aplicaciones de Algoritmos de Enjambre en Machine Learning

##  Descripción

Este repositorio presenta la implementación de distintas aplicaciones de **algoritmos de inteligencia de enjambre** en problemas de aprendizaje automático.

Se desarrollaron soluciones utilizando:

* **Particle Swarm Optimization (PSO)**
* **Artificial Bee Colony (ABC)**

El objetivo es demostrar cómo estos algoritmos pueden resolver problemas de optimización en diferentes etapas del Machine Learning.

---

#  Objetivo

Aplicar algoritmos de enjambre para resolver problemas de optimización en modelos de aprendizaje automático, analizando su comportamiento y resultados.

---

#  Casos de Estudio

##  1. Feature Selection usando ABC

Se emplea el algoritmo **Artificial Bee Colony (ABC)** para seleccionar el subconjunto óptimo de características de un dataset.

### Enfoque

* Representación binaria de características
* Reducción de dimensionalidad
* Mejora del rendimiento del modelo

### Objetivo

Maximizar la precisión usando el menor número de variables posible.

---

##  2. Optimización de Hiperparámetros con PSO

Se implementa **Particle Swarm Optimization (PSO)** para ajustar los hiperparámetros de un modelo Random Forest.

### Dataset

Wine Dataset

* 178 instancias
* 13 atributos
* 3 clases

### Hiperparámetros optimizados

* n_estimators
* max_depth
* min_samples_split
* min_samples_leaf
* max_features

### Configuración

* 20 partículas
* 30 iteraciones
* Validación cruzada (K=3)

### Resultado

* **Accuracy máximo:** 98.88%
* Mejores parámetros encontrados automáticamente

---

##  3. Entrenamiento de Red Neuronal sin Backpropagation

Se propone el uso de algoritmos de enjambre para entrenar redes neuronales sin utilizar gradientes.

### Enfoque

* Optimización directa de pesos y bias
* Cada partícula representa una red neuronal

### Ventajas

* No requiere cálculo de derivadas
* Evita óptimos locales
* Permite exploración global del espacio de soluciones

---

##  4. Clustering usando PSO

Se aplica PSO para resolver un problema de agrupamiento sobre el dataset Iris.

### Dataset

Iris Dataset

* 150 instancias
* 4 características
* 3 clases

### Representación

* 3 centroides → 12 dimensiones

### Configuración

* 30 partículas
* 50 iteraciones

### Métrica

* SSE (Sum of Squared Errors)

### Resultado

* **Mejor fitness:** 29.28
* Agrupamiento coherente de los datos

---

#  Ciclo de los Algoritmos de Enjambre

En todos los casos se sigue el mismo proceso:

1. Representación de la solución
2. Inicialización del enjambre
3. Evaluación (función fitness)
4. Actualización de partículas
5. Evolución iterativa
6. Condición de parada

---

# ⚙️ Tecnologías Utilizadas

* Python
* NumPy
* Scikit-learn
* Matplotlib
* Google Colab / Jupyter Notebook

---

#  Ejecución

Clonar el repositorio:

```bash
https://github.com/Flavio-zt/Algoritmos-de-enjambre.git
```

Abrir los notebooks en:

* Google Colab
* Jupyter Notebook

Ejecutar cada sección paso a paso.

---

#  Conclusiones

Los algoritmos de enjambre demostraron ser eficaces en distintos problemas de Machine Learning, permitiendo optimizar modelos, reducir dimensionalidad y resolver tareas sin depender de métodos tradicionales como el descenso por gradiente.

---

#  Integrantes

* Integrante 1
* Integrante 2
* Integrante 3
* Flavio zapana ticona

---

# 🔗 Repositorio

https://github.com/Flavio-zt/Algoritmos-de-enjambre.git
