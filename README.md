# 🧠 Entrenamiento de RBFNN con Clustering Jerárquico

Este repositorio presenta un nuevo método de entrenamiento para **Redes Neuronales de Función de Base Radial (RBFNN)**.

Tradicionalmente, el entrenamiento de RBFNN se basa en **K-means para la selección y colocación de neuronas**, lo que obliga a fijar previamente el número de neuronas del modelo. Esta elección suele ser arbitraria, dependiente del dataset y difícil de ajustar correctamente.

El objetivo de este trabajo es eliminar esta limitación introduciendo una estrategia basada en **clustering jerárquico**, que permite **seleccionar automáticamente el número de neuronas** a partir de los propios datos, sin necesidad de definirlo de antemano.

---

## ✅ Qué aporta este proyecto

- Selección automática del número de neuronas.
- Entrenamiento dividido en dos etapas bien diferenciadas:
  - Selección de neuronas.
  - Cálculo de pesos.
- Evaluación con datos sintéticos y reales.
- Comparativa frente al enfoque clásico basado en K-means.
- Prueba de escalabilidad.

---

## ⚙️ Flujo general del método

<p align="center">
  <img src="figures/flujo.jpg" width="500" heigh="300">
</p>

## 📊 Resultados

El método propuesto:

- Reduce el coste computacional frente a métodos más complejos.
- Mantiene un alto nivel de precisión.
- Escala razonablemente bien en grandes volúmenes de datos.

---

## 📄 Memoria completa del TFG

Puedes consultar el documento completo del trabajo aquí:

📘 **[Descargar memoria (PDF)](Memoria-mario.fernandez.simon.pdf)**

---

## 👤 Autor

**Mario Fernández Simón**  
Ingeniería Informática (Computación)

---
