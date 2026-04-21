# 🍷 Wine Quality Predictor: Machine Learning aplicado a la Industria Vitivinícola

## Descripción
Este proyecto implementa un modelo de Machine Learning para predecir la calidad del vino tinto en base a sus propiedades físico-químicas (pH, acidez, sulfatos, alcohol, etc.). Está diseñado con un enfoque práctico orientado al negocio, permitiendo a equipos de calidad estandarizar controles y entender con datos duros qué variables químicas impactan positiva o negativamente en el producto final.

## Características Principales
* **Predicción en Tiempo Real:** Interfaz interactiva donde el usuario puede ajustar parámetros de laboratorio y obtener una estimación de calidad (escala 3-8) al instante.
* **Explicabilidad (Feature Importance):** Un modelo no es útil si es una "caja negra". La aplicación incluye visualizaciones que detallan el peso de cada variable en la decisión del algoritmo, aportando transparencia y valor para la toma de decisiones en la bodega.

## Tecnologías Utilizadas
* **Lenguaje:** Python
* **Machine Learning:** Scikit-Learn (Random Forest Classifier)
* **Manipulación de Datos:** Pandas
* **Visualización:** Matplotlib
* **Interfaz y Deploy:** Streamlit

## 🚀 Demo
Podés probar la aplicación interactiva en vivo aquí: ``

## Cómo ejecutarlo localmente
1. Clonar el repositorio.
2. Instalar las dependencias: `pip install -r requirements.txt`
3. Ejecutar la aplicación: `streamlit run app.py`
