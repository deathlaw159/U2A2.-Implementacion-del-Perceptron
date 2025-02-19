# U2A2.-Implementacion-del-Perceptron

##Perceptrón para Clasificación de Solicitudes de Préstamo

Descripción

Este proyecto implementa un perceptrón en Python para clasificar solicitudes de préstamo de una institución financiera. El modelo evalúa cuatro factores clave: puntaje de crédito, ingresos mensuales, monto del préstamo solicitado y relación deuda/ingresos. Utilizando datos de entrenamiento históricos, el perceptrón aprende a determinar si una solicitud de préstamo debe ser aprobada o rechazada.

Requisitos

-Python 3.x

-NumPy

-Estructura del Código

1. Datos de Entrenamiento

Se define un conjunto de datos de entrenamiento que contiene cinco registros con cuatro características cada uno. La salida esperada (y) representa la aprobación (1) o el rechazo (0) del préstamo.

2. Normalización de Datos

Los datos se normalizan utilizando la técnica de min-max scaling, asegurando que todas las variables tengan un rango entre 0 y 1. Esto mejora la eficiencia del entrenamiento y evita que una variable domine sobre las demás.

3. Configuración del Perceptrón

-Se inicializan los pesos y el sesgo con valores aleatorios.

-Se define una tasa de aprendizaje (learning_rate = 0.1).

-Se establecen epochs = 10, que indica el número de veces que el modelo recorrerá los datos para aprender.

-Se utiliza una función de activación escalón que devuelve 1 si el resultado es mayor o igual a cero y 0 en caso contrario.

4. Entrenamiento del Perceptrón

El modelo se entrena ajustando los pesos y el sesgo en cada iteración con base en la diferencia entre la salida esperada y la salida predicha. Esto permite mejorar la capacidad del modelo para clasificar correctamente futuras solicitudes.

5. Evaluación del Modelo

Se ingresa un nuevo conjunto de datos para predecir si un préstamo será aprobado o rechazado. Dependiendo del resultado del perceptrón, el programa imprime un mensaje indicando la decisión final.

Uso

-Para ejecutar el código, simplemente cópielo en un entorno de Python y ejecútelo. El modelo entrenará con los datos proporcionados y evaluará una nueva solicitud de préstamo, indicando si será aprobada o rechazada.

-Mejoras Futuras

-Ajuste de hiperparámetros (tasa de aprendizaje y número de épocas).

-Implementación de un modelo con múltiples neuronas para mejorar la capacidad de clasificación.

Uso de bibliotecas avanzadas como TensorFlow o Scikit-Learn para mejorar el rendimiento del modelo.
