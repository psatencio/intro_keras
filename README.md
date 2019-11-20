Pedro Atencio - 2019

Repositorio del taller - Introducción a las redes neuronales en Keras - desarrollado en la Universidad Nacional del Sur, Bahía Blanca, Argentina.


## Contenido:

1. Conceptos generales
    1. Regresor logistico como una neurona
    2. El grafo de computo.
    3. Descenso del gradiente.
    4. Broadcasting / Vectorization.
        El operador XOR
            Clasificación no-lineal.
            Descomposición lineal.
            Regresores lineales en capas.
        Backpropagation
            Análisis del descenso del gradiente y regla de la cadena.
            Implementacion general utilizando diccionarios.
            Errores y funciones de activación
    Conceptos tecnológicos (tensorflow.keras)
        Bloques de construcción
            Inputs
            Layers
            losses
            optimizers
        Cableado de los bloques: Conexión de los distintos bloques de la red neuronal, desde la entrada hasta la salida.
        Preparación del dataset: Algunos aspectos a tener en cuenta a la hora de organizar los datos.
        Entrenamiento y validación.
            model.compile()
            model.fit()
            history
        Redes de ejemplo: Implementación de algunos ejemplos populares (clasificación, regresión, red convolutiva, etc.)
    Conceptos utilitarios
        Fine-tuning: Utilizar una red pre-entrenada y afinarla para que trabaje con nuestros datos.
        Callbacks: Tomar decisiones durante el proceso de entrenamiento.
        Grid search: Encontrar los mejores parámetros de la red.
        Lamba layers: Construir nuestras propias capas de red neuronal.
        Custom losses: Construir nuestras propias funciones de error.
        Activations: Construir nuestras propias funciones de activación.
