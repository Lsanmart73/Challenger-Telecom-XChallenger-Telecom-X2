
# Proyecto de Análisis de Cancelación de Servicios (Churn) en Telecomunicaciones

Este proyecto utiliza técnicas de aprendizaje automático para predecir la cancelación de servicios (churn) de clientes de telecomunicaciones. Los modelos empleados son la **Regresión Logística** y el **Bosque Aleatorio**, con el objetivo de predecir qué clientes tienen más probabilidades de cancelar su servicio.

## Descripción del Proyecto

El proyecto consta de varias etapas, que incluyen:

1. **Preprocesamiento de los Datos**: 
   - Carga del conjunto de datos y eliminación de columnas irrelevantes.
   - Normalización de las características para mejorar el rendimiento de los modelos.
   - División del conjunto de datos en entrenamiento y prueba.

2. **Entrenamiento de Modelos**: 
   - Se entrenaron dos modelos: **Regresión Logística** y **Bosque Aleatorio**.
   - Los modelos fueron evaluados utilizando métricas como el **Reporte de Clasificación** y la **Puntuación ROC-AUC**.

3. **Evaluación de Resultados**: 
   - Se evaluó el rendimiento de ambos modelos en términos de precisión y capacidad predictiva.
   - Se identificaron las variables más influyentes en la predicción de la cancelación de clientes.

## Requisitos

Asegúrate de tener instalados los siguientes paquetes de Python:

- pandas
- scikit-learn
- matplotlib
- seaborn

Puedes instalar estos paquetes utilizando pip:

```bash
pip install pandas scikit-learn matplotlib seaborn
```

## Cómo Ejecutar el Proyecto

1. Descarga el archivo de datos procesados `datos_procesados.csv` y colócalo en el directorio raíz del proyecto.
2. Ejecuta el cuaderno Jupyter `TelecomX2.ipynb` para realizar el análisis completo.
3. El cuaderno generará las predicciones y evaluaciones de los modelos.

## Conclusiones

El proyecto demuestra cómo el uso de modelos de aprendizaje automático puede ayudar a predecir la cancelación de clientes en empresas de telecomunicaciones. Las conclusiones clave incluyen:

- **Desempeño de los Modelos**: El **Bosque Aleatorio** mostró un mejor rendimiento comparado con la **Regresión Logística**.
- **Importancia de las Variables**: Las variables más relevantes incluyen el tipo de contrato, el método de pago y los servicios adicionales contratados.
- **Recomendaciones**: Personalizar las ofertas y enfoques de fidelización según las características de los clientes puede reducir las tasas de cancelación.


