# Spaceship Titanic: Predicción de Pasajeros Transportados

Este es el repositorio para la competición Kaggle "Spaceship Titanic: Predicción de Pasajeros Transportados". En este proyecto, utilizaremos técnicas de ciencia de datos y aprendizaje automático para predecir qué pasajeros fueron transportados a otra dimensión después del choque de la Spaceship Titanic con una anomalía espaciotemporal.

## Introducción

### Resumen del problema

Bienvenidos al año 2912, donde se necesitan tus habilidades en ciencia de datos para resolver un misterio cósmico. La Spaceship Titanic, un transatlántico interestelar, chocó con una anomalía espaciotemporal, lo que resultó en la desaparición de casi la mitad de sus pasajeros que fueron transportados a una dimensión alternativa. El desafío es predecir qué pasajeros fueron transportados utilizando los registros recuperados del sistema informático dañado de la nave.

### Conjunto de Datos

El conjunto de datos para esta competición contiene registros personales de los pasajeros a bordo del Spaceship Titanic antes del desafortunado incidente con la anomalía espaciotemporal. El repositorio contiene dos archivos principales:

- `train.csv`: Contiene registros personales para aproximadamente dos tercios (~8700) de los pasajeros, que se utilizarán como datos de entrenamiento.
- `test.csv`: Contiene registros personales para el tercio restante (~4300) de los pasajeros, que se utilizarán como datos de prueba.

Ambos archivos contienen información como identificación de pasajero, planeta de origen, estado de sueño criogénico, número de cabina, planeta de destino, edad, estado de VIP y gastos en diversas instalaciones de lujo en la nave.

### Características del conjunto de datos

Las principales características del conjunto de datos incluyen:

- **PassengerId**: Identificador único para cada pasajero.
- **Cabin**: Número de la cabina donde se aloja el pasajero.
- **HomePlanet**: Planeta de origen del pasajero (Europa, Tierra o Marte).
- **Destination**: Planeta de destino al que el pasajero iba a desembarcar.
- **Age**: Edad del pasajero.
- **CryoSleep**: Indicador de si el pasajero optó por entrar en animación suspendida durante el viaje.
- **VIP**: Indicador de si el pasajero ha pagado por un servicio VIP especial durante el viaje.
- **RoomService**, **FoodCourt**, **ShoppingMall**, **Spa**, **VRDeck**: Gastos del pasajero en diferentes comodidades de lujo.
- **Name**: Nombre y apellido del pasajero.
- **Transported**: Variable objetivo que indica si el pasajero fue transportado a otra dimensión.

## Metodología

La metodología recomendada para abordar este problema es a través de un proceso iterativo, que consta de los siguientes pasos:

1. Análisis exploratorio de datos (EDA) para comprender la distribución de las características y su relación con la variable objetivo.
2. Limpieza de los datos, tratando los valores perdidos y eliminando o transformando los valores atípicos.
3. Ingeniería de características para extraer la máxima información de las características disponibles.
4. Entrenamiento de diferentes modelos de clasificación y validación de los mismos utilizando técnicas como la validación cruzada.
5. Ajuste de hiperparámetros para mejorar el rendimiento del modelo.
6. Evaluación de los modelos y selección del mejor modelo para hacer predicciones en el conjunto de prueba.
7. Generación de predicciones en el conjunto de prueba y presentación de resultados.

## Contribuciones y colaboración

Si estás interesado en colaborar en este proyecto, ¡eres bienvenido! Puedes hacer fork de este repositorio, trabajar en tu propia rama y enviar un pull request con tus contribuciones.

## Licencia

Este proyecto está bajo la Licencia MIT. Puedes consultar el archivo [LICENSE](./LICENSE) para más detalles.

## Contacto

Si tienes alguna pregunta o quieres contactarme con respecto a este proyecto, puedes enviarme un correo electrónico a [josevillalbajimenez@email.com].
