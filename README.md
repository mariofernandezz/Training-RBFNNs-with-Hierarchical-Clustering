# Training-RBFNNs-with-Hierarchical-Clustering
Este proyecto se centra en el diseño, la implementación y la evaluación de un nuevo método
de entrenamiento para Redes Neuronales de Función de Base Radial (RBFNN). El proceso
de entrenamiento se divide en dos bloques. El primero se encarga de buscar el número
óptimo de neuronas usando clustering jerárquico y su colocación usando K-means. El
segundo calcula los pesos usando diferentes técnicas de regularización. Los métodos de
regularización usados son: Ridge, Lasso, AIC, y dos combinaciones secuenciales (Lasso +
Ridge y AIC + Ridge).
El trabajo incluye un marco experimental exhaustivo sobre tareas de regresión usando
tanto conjuntos de datos sintéticos que simulan funciones de una variable con diferentes
niveles de ruido como conjuntos de datos de la vida real. Para cada experimento se realiza
una comparativa entre los diferentes métodos de regularización observando las diferencias
para diversas métricas de evaluación. Además, se compara el rendimiento de nuestro
método para seleccionar neuronas con el método comúnmente más usado, K-means. Por
último, se realiza una prueba de escalabilidad con grandes conjuntos de datos.
La evaluación experimental confirma la eficacia de los modelos RBFNN, proporcionando
estimaciones precisas y eficientes. El análisis comparativo revela que el modelo secuencial
AIC + Ridge obtiene un rendimiento cercano al estado del arte con un costo computa￾cional muy reducido en comparación con modelos más complejos en literatura científica.
Por otro lado, la prueba de escalabilidad muestra que el modelo alcanza una precisión
respetable para el costo computacional que conlleva, lo que lo convierte en una opción
sólida para grandes conjuntos de datos que puede ejecutarse cómodamente en hardware
de baja potencia.
