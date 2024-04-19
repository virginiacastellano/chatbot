# Chatbot IA

Este chatbot utiliza inteligencia artificial para interactuar con los usuarios. Funciona mediante la clasificación de mensajes en categorías predefinidas, las cuales están especificadas en el archivo `intents.json`. Estas categorías representan los distintos tipos de mensajes que el chatbot puede reconocer y responder.

## Estructura del Proyecto

El proyecto está organizado en tres archivos principales:

1. **intents.json**: En este archivo se definen las categorías de mensajes (intenciones) junto con los patrones de mensajes asociados y las posibles respuestas para cada intención.

2. **training.py**: Aquí se lleva a cabo el entrenamiento del modelo de clasificación utilizando los datos del archivo `intents.json`. Se procesan los datos y se genera un modelo capaz de predecir la intención de un mensaje nuevo.

3. **chatbot.py**: Una vez que el modelo ha sido entrenado, este archivo se utiliza para interactuar con los usuarios. El chatbot recibe un mensaje del usuario, lo clasifica utilizando el modelo entrenado y proporciona una respuesta adecuada basada en la intención detectada.

## Instrucciones para Probar

Para probar el chatbot, sigue estos pasos:

1. Modifica los patrones y las respuestas en el archivo `intents.json` según las necesidades del proyecto.

2. Ejecuta el archivo `training.py` para entrenar el modelo. Puedes ajustar los parámetros del modelo y del optimizador según sea necesario.

3. Una vez completado el entrenamiento, ejecuta el archivo `chatbot.py` para interactuar con el chatbot. Introduce mensajes de prueba y observa las respuestas proporcionadas.

¡Disfruta utilizando el chatbot y explorando las capacidades de la inteligencia artificial!