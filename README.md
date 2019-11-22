Pedro Atencio - 2019

Repositorio del taller - Introducción a las redes neuronales en Keras - desarrollado en la Universidad Nacional del Sur, Bahía Blanca, Argentina.


## Contenido:

1. Conceptos generales (días 1 y 2)
    1. Regresor logistico como una neurona
        1. Análisis desde el grafo de cómputo.
        2. Implementación tradicional.
        3. Broadcasting / Vectorization.
        4. Implementación vectorizada.
        5. Descenso del gradiente.
    2. El operador XOR
        1. Clasificación no-lineal.
        2. XOR y su descomposición lineal.
        3. Regresores lineales en capas.
    3. Red Neuronal y Backpropagation (descenso del gradiente generalizado)
        - Notación.
        - Forward propagation.
        - Backpropagation.
        - Errores y funciones de activación.
2. Conceptos tecnológicos (tensorflow.keras) (días 3 y 4)
    1. Bloques de construcción
        1. Inputs
        2. Layers
        3. losses
        4. optimizers
    2. Cableado de los bloques
        1. Construcción como lista.
        2. Agregación de capas (model.add).
        3. Capa Input y conexión por capa.
    3. Preparación del dataset
        1. Estructura del dataset.
        2. Train / Test (dataset split).
    4. Entrenamiento y validación.
        1. model.compile()
        2. model.fit()
        3. history
    5. Redes de ejemplo
        1. Clasificación y Regresión.
        2. Convolución 2D (concepto).
        3. Series de tiempo (redes recurrentes).
3. Conceptos utilitarios (día 5)
    1. Fine-tuning: Utilizar una red pre-entrenada y afinarla para que trabaje con nuestros datos.
    2. Callbacks: Tomar decisiones durante el proceso de entrenamiento.
    3. Grid search: Encontrar los mejores parámetros de la red.
    4. Lamba layers: Construir nuestras propias capas de red neuronal.
    5. Custom losses: Construir nuestras propias funciones de error.
    6. Activations: Construir nuestras propias funciones de activación.
