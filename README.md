# Científico de datos
<br>
<br>
<br>

# **Acerca de mi**
Maestría en Electrónica y Comunicaciones con certificado y en transición a Data Scientist y experiencia en dirigir proyectos de nuevos productos.  Durante la certificación en Data Scientist, desarrolle múltiples proyectos para diferentes empresas enfocados en tomas de decisiones de negocio para nuevas estrategias, utilizando grandes volúmenes de datos y visualizaciones para mayor claridad. Dentro de las herramientas o técnicas utilizadas para dichos proyectos se encuentran Python, SQL, Big Data, Machine Learning y Data Wrangling. 
<br>
<br>
<br>

# **Herramientas**
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jupyter/jupyter-original.svg" alt="Jupyter" width="40" height="40"/> &nbsp;
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="40" height="40"/> &nbsp;
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg" alt="Pandas" width="40" height="40"/> &nbsp;
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/scikitlearn/scikitlearn-original.svg" alt="scikit-learn" width="40" height="40"/> &nbsp;
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/chartjs/chartjs-original.svg" alt="Time Series Analysis" width="40" height="40"/> &nbsp;
<img src="assets/statsmodels.png" alt="Statsmodels" width="40" height="40"/> &nbsp;
<img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="TensorFlow" width="40" height="40"/> &nbsp;
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/matplotlib/matplotlib-original.svg" alt="Matplotlib" width="40" height="40"/> &nbsp;
<img src="assets/seaborn-logo.png" width="40" height="40"/> &nbsp;
<img src="assets/Tableau-Logo.png" width="40" height="40"/> &nbsp;
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/azuresqldatabase/azuresqldatabase-original.svg" alt="SQL" width="40" height="40"/> &nbsp;
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-plain-wordmark.svg" alt="AWS" width="40" height="40"/>
<br>
<br>
<br>

# **Proyectos**
<br>
<br>

## Predicción de clientes que se dan de baja

### **Objetivo**
Desarrollar un modelo predictivo para anticipar la tasa de cancelación de clientes en Interconnect, operador de telecomunicaciones, con el fin de implementar estrategias de retención mediante promociones y planes especiales.

### **Alcance del Proyecto**
Servicios analizados: telefonía fija, internet (DSL y fibra óptica), seguridad digital, soporte técnico, almacenamiento en la nube, streaming de TV y películas.

Datos utilizados: información contractual y de planes de clientes, con múltiples métodos de pago y periodos de contratación.

### **Metodología**
Análisis exploratorio y limpieza de cuatro conjuntos de datos.

Unificación y balanceo de clases, con visualización de tendencias.

Preprocesamiento: escalado de variables numéricas y codificación de categóricas.

Entrenamiento de modelos con ajuste de hiperparámetros.

Evaluación con métricas clave: AUC-ROC, F1, recall, precisión y accuracy.

### **Modelos Evaluados**
Dummy Classifier: referencia inicial (ROC 0.50).

Logistic Regression: mejora significativa (ROC 0.85, F1 0.64).

Decision Tree: desempeño sólido (ROC 0.84, F1 0.63).

Random Forest: mejor resultado global (ROC 0.86 en prueba, F1 0.66, accuracy 0.79).

 <img src="assets/resultados-metrica.png" alt="Results" width="600">

### **Resultados Clave**
El modelo predijo una tasa de cancelación del 35% vs. 27% real, con un margen de sobreestimación del 8%.

Identificación de servicios más afectados por la cancelación: fibra óptica, telefonía fija y streaming.

<img src="assets/servicios-cancelacion.png" alt="Churned" width="600">

Herramientas utilizadas: <br>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jupyter/jupyter-original.svg" alt="Jupyter" width="40" height="40"/> &nbsp;
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="40" height="40"/> &nbsp;
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg" alt="Pandas" width="40" height="40"/> &nbsp;
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/matplotlib/matplotlib-original.svg" alt="Matplotlib" width="40" height="40"/> &nbsp;
<img src="assets/seaborn-logo.png" width="40" height="40"/> &nbsp;
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/scikitlearn/scikitlearn-original.svg" alt="scikit-learn" width="40" height="40"/>
<br>
<br>

## Predicción de demanda de taxis en aeropuerto

### **Objetivo**
Desarrollar un modelo predictivo para anticipar la cantidad de pedidos de taxis en aeropuertos durante la próxima hora, optimizando la disponibilidad de conductores en horarios pico y mejorando la eficiencia operativa de la compañía Sweet Lift Taxi.

### **Alcance del Proyecto**
**Datos utilizados:** históricos de pedidos de taxis en aeropuertos.

**Transformación temporal:** series convertidas a horas y días para identificar tendencias y estacionalidad.

**Análisis exploratorio:** revisión de patrones, tendencias y residuales en diferentes escalas temporales.

### **Metodología**
Carga y limpieza de datos en Jupyter Notebook.

Visualización de series temporales para detectar estacionalidad y tendencias.

Entrenamiento de modelos con ajuste de parámetros.

Validación en conjunto de prueba con métrica clave: RMSE < 48.

### **Modelos Evaluados**
Regresión Lineal: desempeño limitado, no cumple con el objetivo.

Árbol de Decisión: RMSE < 48, cumple con el requisito.

Random Forest: mejor desempeño global, RMSE más bajo y mayor capacidad de generalización.

### **Resultados Clave**
Dos modelos (Árbol de Decisión y Random Forest) cumplen con el objetivo de RMSE < 48.

El Random Forest se posiciona como la mejor opción para predecir la demanda horaria de taxis.

Se identificaron patrones de estacionalidad y tendencias claras entre marzo y octubre de 2018.

Herramientas utilizadas: <br>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jupyter/jupyter-original.svg" alt="Jupyter" width="40" height="40"/> &nbsp;
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="40" height="40"/> &nbsp;
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg" alt="Pandas" width="40" height="40"/> &nbsp;
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/matplotlib/matplotlib-original.svg" alt="Matplotlib" width="40" height="40"/> &nbsp;
<img src="assets/statsmodels.png" alt="Statsmodels" width="40" height="40"/> &nbsp;
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/scikitlearn/scikitlearn-original.svg" alt="scikit-learn" width="40" height="40"/> &nbsp;
<br>
<br>

## Proyecto de visión artificial para cumplimiento legal

### **Objetivo**
Desarrollar un modelo de visión artificial que permita verificar la edad de clientes en supermercados al momento de comprar alcohol, garantizando el cumplimiento de la normativa y reduciendo riesgos legales para la cadena Good Seed.

### **Alcance del Proyecto**
**Datos utilizados:** fotografías de personas con edad conocida.

**Contexto de aplicación:** cámaras en áreas de pago que se activan ante compras de alcohol.

**Meta del modelo:** lograr un Error Absoluto Medio (MAE) < 8 años en la predicción de edad.

### **Metodología**
**Análisis exploratorio de datos:** revisión de distribución de edades y validación de imágenes.

Entrenamiento de modelos de visión artificial con redes neuronales convolucionales (CNN).

**Uso de arquitecturas avanzadas:** ResNet50, capas de GlobalAveragePooling2D y Dense.

Optimización con Adam y evaluación mediante métricas MAE y MSE.

### **Resultados Clave**
Reducción del error de 11.47 a 7.21 años, cumpliendo con el objetivo de MAE < 8.

El modelo alcanzó la meta en solo 4 épocas, mostrando rápida convergencia.

Diferencia entre entrenamiento y validación dentro de rangos aceptables.

Mayor presencia de edades entre 23 y 30 años en el dataset, lo que permitió validar tendencias.

Herramientas: <br>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jupyter/jupyter-original.svg" alt="Jupyter" width="40" height="40"/> &nbsp;
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="40" height="40"/> &nbsp;
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg" alt="Pandas" width="40" height="40"/> &nbsp;
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/matplotlib/matplotlib-original.svg" alt="Matplotlib" width="40" height="40"/> &nbsp;
<img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="TensorFlow" width="40" height="40"/> &nbsp;
<br>
<br>

# **Educación**
* **Científico de datos**, Tripleten bootcamp (2026) <br>
* **Electrónica y Comunicaciones**, Maestría en Tecnológico de Monterrey (2014) <br>
* **Electrónica y Comunicaciones**, Ingeniería en Tecnológico de Monterrey (2007)


