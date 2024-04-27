# Proyecto-Seguros-de-coches
En este repositorio se reporta el proyecto de Seguro de coches.
# Descripción del Proyecto:
El proyecto se divide en dos partes principales:
1.	Análisis de Datos:

    * Generación de un conjunto de datos simulados que incluya información sobre pólizas de seguro, siniestros, tipo de cobertura, modelo del coche, entre otros.

    * Exploración y análisis de los datos utilizando técnicas como visualizaciones, análisis estadístico y correlaciones.

    * Aplicación de al menos seis análisis diferentes, incluyendo distribución de montos de reclamo, relación entre variables, análisis de tendencias y correlaciones.

2.	Desarrollo y Despliegue de Modelo Predictivo:
    
    * Selección de un modelo de Machine Learning adecuado para predecir alguna variable relevante basada en el conjunto de datos analizado.

    * Entrenamiento del modelo seleccionado utilizando técnicas de validación cruzada y ajuste de hiperparámetros si es necesario.

    * Desarrollo de una aplicación web utilizando Streamlit que permita a los usuarios introducir datos y obtener predicciones del modelo en tiempo real.

    * Despliegue de la aplicación en un entorno accesible para su uso.

Variables Generadas:

    Número de póliza: Se asigna un identificador único a cada póliza de seguro generado. El número de póliza sigue el formato "PXXXXX", donde "XXXXX" es un número único rellenado con ceros a la izquierda para mantener una longitud constante de cinco dígitos.

    Fechas de inicio y vencimiento: Se generan fechas de inicio y vencimiento aleatorias dentro del rango de tiempo comprendido entre el 1 de enero de 2022 y el 31 de diciembre de 2025.

    Tipo de cobertura: Se asigna aleatoriamente uno de los siguientes tipos de cobertura a cada póliza de seguro: responsabilidad civil, cobertura total, cobertura de colisión, cobertura amplia y cobertura de robo.

    Modelo del coche: Se elige aleatoriamente un modelo de automóvil de una lista predefinida que incluye marcas como Toyota Corolla, Honda Civic, Ford Focus, Chevrolet Cruze y Nissan Sentra. Las probabilidades de selección están predefinidas para cada modelo.

    Año del coche: Se genera aleatoriamente el año de fabricación del automóvil asegurado, variando entre 2010 y 2022.

    Valor asegurado: Se asigna un valor asegurado aleatorio entre $10,000 y $50,000 para cada póliza de seguro.

    Deducible: Se elige aleatoriamente un deducible de $500, $600 o $700 para cada póliza de seguro.

    Estado del seguro: Se asigna aleatoriamente el estado del seguro como "Al día" o "Vencido" para cada póliza.

    Gastos médicos y Daños a terceros: Se generan aleatoriamente valores binarios (0 o 1) para indicar la presencia o ausencia de siniestros relacionados con gastos médicos y daños a terceros, respectivamente.
