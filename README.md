# Car-Price-Prediction

Este proyecto tiene como objetivo desarrollar un modelo de predicción de precios de automóviles que permita estimar el valor de un vehículo en función de sus características principales.

Para lograr este objetivo, se utilizará un conjunto de datos obtenido de Kaggle, que contiene información detallada sobre 10,000 automóviles. Este dataset incluye variables como la marca, el modelo, el año de fabricación, el tamaño del motor, el tipo de combustible, el tipo de transmisión, el kilometraje, el número de puertas, la cantidad de dueños anteriores y, por supuesto, el precio. Estas variables serán analizadas y utilizadas para entrenar un modelo de machine learning que pueda predecir el precio de un automóvil con base en sus características.

El conjunto de datos utilizado en este proyecto está diseñado específicamente para la predicción de precios de automóviles. A continuación, se describe la estructura y las columnas del dataset:

Descripción de las Columnas:

- Brand (Marca): Especifica la marca del automóvil (por ejemplo, Toyota, BMW, Ford).

- Model (Modelo): Indica el modelo específico del automóvil (por ejemplo, Corolla, Focus, X5).

- Year (Año): Representa el año de fabricación del automóvil. Los años más recientes suelen estar asociados con precios más altos.

- Engine_Size (Tamaño del Motor): Especifica el tamaño del motor en litros (L). Los motores más grandes generalmente se correlacionan con precios más altos.

- Fuel_Type (Tipo de Combustible): Indica el tipo de combustible que utiliza el automóvil:

- Petrol (Gasolina): Automóviles que funcionan con gasolina.

- Diesel: Automóviles que funcionan con diesel.

- Hybrid (Híbrido): Automóviles que utilizan tanto combustible como electricidad.

- Electric (Eléctrico): Automóviles completamente eléctricos.

- Transmission (Transmisión): Especifica el tipo de transmisión del automóvil:

- Manual: Transmisión manual.

- Automatic: Transmisión automática.

- Semi-Automatic: Transmisión semi-automática.

- Mileage (Kilometraje): Representa la distancia total que ha recorrido el automóvil, medida en kilómetros. Un menor kilometraje generalmente indica un precio más alto.

- Doors (Puertas): Indica el número de puertas que tiene el automóvil. Los valores comunes son 2, 3, 4 o 5 puertas.

- Owner_Count (Número de Dueños): Representa la cantidad de dueños anteriores que ha tenido el automóvil. Un menor número de dueños generalmente indica un precio más alto.

- Price (Precio): Es el precio estimado de venta del automóvil. Este valor se calcula en función de varios factores, como el año de fabricación, el tamaño del motor, el kilometraje, el tipo de combustible y la transmisión.
