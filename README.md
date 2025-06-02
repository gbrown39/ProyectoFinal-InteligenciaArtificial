# ProyectoFinal-InteligenciaArtificial
Proyecto-final-reconocimiento-de-actividad-F-sica-con-seguimiento-de-movimiento
Este proyecto integra Arduino UNO y el sensor MPU6050 para recolectar datos de movimiento en tiempo real, los cuales son procesados mediante Machine Learning (Random Forest en Python) para clasificar actividades físicas como caminar, correr, estar parado o detectar caídas. Además, los resultados se visualizan en Power BI mediante gráficas interactivas, permitiendo el análisis por usuario y la detección de eventos críticos. Todo el sistema ha sido desarrollado con enfoque educativo y práctico para aplicaciones en salud, deporte o monitoreo personalizado.Ya que tiene muchos tipos de aplicacion.

Fases del Desarrollo:
•	Fase 1: Recolección de datos del sensor MPU6050 vía Arduino.
•	Fase 2: Limpieza y preprocesamiento de datos en Python.
•	Fase 3: Entrenamiento de un modelo de Machine Learning (Decision Tree o Random Forest).
•	Fase 4: Clasificación en tiempo real desde datos seriales del sensor.
•	Fase 5: Registro automático de los resultados en un archivo .csv.
•	Fase 6: Visualización de los datos y eventos críticos en Power BI.
