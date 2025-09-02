# Telco Customer Churn – Análisis y Predicción

<img src="images/logo.png" alt="Girl in a jacket" width="200" >


Este proyecto utiliza el dataset **Telco Customer Churn** de Kaggle, que contiene información sobre clientes de telecomunicaciones, incluyendo si abandonaron el servicio (“churn”), los servicios contratados (teléfono, internet, soporte técnico, etc.), datos de cuenta (tenencia, tipo de contrato, pago) y demográficos (género, dependientes, etc.) 

> Más detalles del dataset en [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)   

## Objetivo del proyecto

* Comprender los factores que influyen en el churn de clientes de telecomunicaciones.
* Desarrollar un modelo predictivo para identificar clientes en riesgo de abandono.
* Proveer una visualización interactiva para explorar los datos y los resultados de los modelos.

##  Enlaces del proyecto

- 🌐 **Aplicación desplegada en Streamlit Cloud**: [Telco Customer Churn](https://telco-churn-example.streamlit.app/)

- 📓 **Código en Google Colab**: [Telco Customer Churn](https://colab.research.google.com/drive/1WsiD8KQAxMBivJF0JDvXIXdKqXtYU1Rc?usp=sharing)



##  Estructura del proyecto

```text
├─── code   # Carpeta con notebooks 
├─── data   # Carpeta con datos
├─── images # Carpeta con imágenes
├─── .gitignore
├─── app.py
├─── LICENSE
├─── README.md
├─── requirements.txt
└── README.md
````



## Descripción de componentes

* `app.py`:
  Presenta una interfaz interactiva donde puedes:

  * Cargar y visualizar datos.
  * Mostrar estadísticas descriptivas y gráficos.
  * Ejecutar modelo de predicción de churn (por ejemplo, regresión logística o árbol de decisión).

* `notebooks/Telco-Customer-Churn.ipynb`:

  * **Carga y limpieza de datos**
  * **Análisis exploratorio (EDA)**
  * **Ingeniería de características** (codificación, escalamiento, etc.)
  * **Entrenamiento y evaluación de modelos**
  * **Visualización de métricas** (confusión, métricas de rendimiento)



## Cómo usar el proyecto

### Con Streamlit Cloud

1. Abre el enlace a la app en Streamlit Cloud.
2. Explora la aplicación: realiza visualizaciones interactivas y predicciones de churn.

### En Google Colab

1. Abre el cuaderno en Colab.
2. Ejecuta las celdas paso a paso para reproducir el análisis y entrenamiento.
3. Puedes modificar o extender los análisis a tu gusto.



## Requisitos

Las dependencias principales incluyen (pero pueden variar):

```text
pandas
numpy
scikit-learn
streamlit
matplotlib
seaborn
```

Instálalas con:

```bash
pip install -r requirements.txt
```

## Licencia

Este proyecto está bajo la licencia MIT. Si usas este código o datos, por favor menciona esta fuente.
