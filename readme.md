https://chatgpt.com/c/c40b4ef6-48a1-459a-8438-0b31ebc75d87


## Que es la estadistica descriptiva?

La estadística descriptiva es una rama de la estadística que se encarga de recolectar, organizar, analizar y presentar datos de manera resumida. 
Su objetivo principal es describir y comprender las características básicas de un conjunto de datos a través de medidas cuantitativas y representaciones visuales.

* Algunas de las herramientas y técnicas más comunes de la estadística descriptiva incluyen:

  - Medidas de tendencia central 
  - Medidas de dispercion 
  - Medidas de forma
  - Representaciones visuales


## ¿Qué significa "mentir con la estadística"?

Mentir con la estadística se refiere a la utilización de técnicas estadísticas o la presentación de datos de manera que se manipulen las percepciones, 
se distorsionen los hechos, o se engañe deliberadamente al público. Aunque la estadística es una herramienta poderosa para analizar datos y sacar conclusiones, 
su mal uso puede llevar a conclusiones incorrectas o engañosas.

* Ejemplos comunes de cómo se puede "mentir con la estadística":

  - Seleccion sesgada de datos
  - Manipulacion de escalas en graficos
  - Promedios engañoso 
  - Muestra no representativa 
  - Confundir correlacion con causalidad
  - uso de porcentajes confusos
  - omision de variabilidad

Es importante entender cómo se puede "mentir con la estadística" porque nos permite ser consumidores críticos de la información. 
En un mundo donde los datos y las estadísticas se utilizan para apoyar decisiones en política, salud, economía, y otros campos, 
ser consciente de estas manipulaciones puede ayudarnos a cuestionar la validez de los argumentos presentados y a buscar una comprensión más profunda de la realidad.


## Que es un flujo de trabajo en data science? 

Un flujo de trabajo en Data Science se refiere al conjunto de pasos o procesos que un científico de datos sigue para desarrollar un proyecto de análisis de datos, 
desde la formulación de un problema hasta la implementación de un modelo predictivo y la comunicación de los resultados. 
Aunque los detalles específicos pueden variar según el proyecto, el flujo de trabajo típico en Data Science generalmente incluye las siguientes etapas:

- Definicion del problema 
- Recoleccion de datos
- Limpieza y preparacion de los datos
  * Tareas comunes:
    - Manejo de valores faltantes.
    - Eliminación de duplicados.
    - Normalización y escalado de variables.
    - Transformaciones de características (por ejemplo, convertir fechas en variables numéricas).

- Análisis Exploratorio de Datos (EDA)
  * Objetivo: Explorar los datos para descubrir patrones, detectar anomalías, probar hipótesis, y entender mejor la estructura de los datos.
  * Herramientas comunes: Gráficos, estadísticas descriptivas, y análisis de correlación.

- Selección y Construcción de Modelos
- Evaluación del Modelo
- Implementación
- Comunicación y Visualización de Resultados
- Monitoreo y Mantenimiento

__Flujo de Trabajo Resumido:__  Definición del Problema → Recolección de Datos → Limpieza y Preparación de Datos → Análisis Exploratorio de Datos → Selección y Construcción de Modelos → Evaluación del Modelo → Implementación → Comunicación y Visualización de Resultados → Monitoreo y Mantenimiento


### Que es el data Ingestion (Ingestión de Datos)?

__Definición:__ La ingesta de datos es el proceso de recopilar, importar y cargar datos desde diferentes fuentes en un sistema de almacenamiento centralizado, 
como un data warehouse o un sistema de procesamiento de datos. 
Esto incluye datos estructurados, semiestructurados y no estructurados provenientes de bases de datos, archivos planos, APIs, sensores, etc.

__Aplicación en Data Science:__ Este es el primer paso en un proyecto de Data Science, ya que los datos deben estar accesibles y disponibles antes de cualquier análisis. 
Un flujo de trabajo bien diseñado garantiza que los datos sean ingeriros de manera eficiente, precisa y en el formato correcto para el análisis posterior.

__Roles involucrados:__ Data Engineers, Data Architects.


### Data Visualization (Visualización de Datos)

__Definición:__ La visualización de datos es el proceso de representar gráficamente los datos para facilitar su comprensión y análisis. Esto incluye gráficos, tablas, mapas, y dashboards interactivos.

__Aplicación en Data Science:__ La visualización de datos se utiliza para explorar datos de manera visual, identificar patrones, tendencias, y anomalías. 
Es una herramienta clave durante el análisis exploratorio de datos (EDA) y también en la comunicación de los resultados a los stakeholders.

__Roles involucrados:__ Data Scientists, Data Analysts, Business Intelligence Analysts.


### Data Preparation (Preparación de Datos)

__Definición:__ La preparación de datos es el proceso de limpiar, transformar, y estructurar los datos en un formato adecuado para su análisis. 
Esto incluye la eliminación de valores atípicos, manejo de datos faltantes, normalización, codificación de variables categóricas, y creación de nuevas características.

__Aplicación en Data Science:__ La calidad de los datos es crucial para el éxito de cualquier modelo predictivo. Una adecuada preparación de datos asegura que los datos estén listos para el modelado, reduciendo el ruido y mejorando la precisión del modelo.

__Roles involucrados:__ Data Scientists, Data Engineers.


### Model Training (Entrenamiento de Modelos)

__Definición:__ El entrenamiento de modelos es el proceso de utilizar datos de entrenamiento para enseñar a un modelo de machine learning a hacer predicciones. 
Durante este paso, el modelo ajusta sus parámetros para minimizar el error en las predicciones.

__Aplicación en Data Science:__ El entrenamiento de modelos es fundamental para construir un sistema que pueda predecir o clasificar datos nuevos basándose en el conocimiento adquirido a partir de los datos de entrenamiento. Diferentes algoritmos de machine learning pueden ser entrenados en función del problema a resolver.

__Roles involucrados:__ Data Scientists, Machine Learning Engineers.


### Model Evaluation (Evaluación de Modelos)

__Definición:__ La evaluación de modelos implica medir el rendimiento del modelo entrenado utilizando un conjunto de datos de prueba o validación, 
y compararlo contra las métricas predefinidas para determinar su efectividad.

__Aplicación en Data Science:__ Esta etapa es crucial para asegurarse de que el modelo no esté sobreajustado (overfitting) o subajustado (underfitting). 
Se utilizan métricas como __precisión, recall, F1-score, AUC-ROC, error cuadrático medio__, entre otras, para evaluar el modelo.

__Roles involucrados:__ Data Scientists, Machine Learning Engineers.


### Model Validation (Validación de Modelos)

__Definición:__ La validación de modelos es el proceso de verificar que el modelo funciona correctamente en datos no vistos (de validación) y que las decisiones del modelo son generalizables y no solo aplicables al conjunto de datos de entrenamiento.

__Aplicación en Data Science:__ Este paso asegura que el modelo es robusto y puede ser aplicado a nuevos datos de manera confiable. 
Se pueden utilizar técnicas como validación cruzada (cross-validation) y análisis de sensibilidad para validar el modelo.

__Roles involucrados:__ Data Scientists, Machine Learning Engineers.


### Model Serving (Servicio de Modelos)

__Definición:__ El servicio de modelos se refiere al despliegue del modelo en un entorno de producción donde puede ser utilizado para hacer predicciones en tiempo real o como parte de un proceso automatizado.

__Aplicación en Data Science:__ Una vez que un modelo ha sido entrenado, evaluado y validado, debe ser implementado para ser utilizado en aplicaciones del mundo real. 
Esto podría involucrar la creación de APIs que permiten a otros sistemas acceder al modelo y obtener predicciones.

__Roles involucrados:__ Machine Learning Engineers, DevOps Engineers.


### End User Interface (Interfaz de Usuario Final)

__Definición:__ La interfaz de usuario final es el punto de interacción entre el sistema y los usuarios. 
En Data Science, esto puede ser un dashboard interactivo, una aplicación web, una API, o cualquier otra forma en que los usuarios accedan a las predicciones y resultados del modelo.

__Aplicación en Data Science:__ La interfaz de usuario final es crucial para asegurar que los resultados del análisis de datos o las predicciones del modelo sean fácilmente accesibles y utilizables por los usuarios finales. Una buena interfaz permite a los usuarios tomar decisiones informadas basadas en los datos.

__Roles involucrados:__ Data Scientists, Data Analysts, UX/UI Designers, Software Engineers.


### Resumen del Flujo de Trabajo y Roles

  - __Data Ingestion:__ Recopilación de datos para análisis. 
    __Roles:__ Data Engineers, Data Architects.
  - __Data Visualization:__ Representación gráfica de datos. __Roles:__ Data Scientists, Data Analysts.
  - __Data Preparation:__ Limpieza y transformación de datos. __Roles:__ Data Scientists, Data Engineers.
  - __Model Training:__ Entrenamiento del modelo de machine learning. __Roles:__ Data Scientists, Machine Learning Engineers.
  - __Model Evaluation:__ Medición del rendimiento del modelo. __Roles:__ Data Scientists, Machine Learning Engineers.
  - __Model Validation:__ Verificación de la generalización del modelo. __Roles:__ Data Scientists, Machine Learning Engineers.
  - __Model Serving:__ Despliegue del modelo en producción. __Roles:__ Machine Learning Engineers, DevOps Engineers.
  - __End User Interface:__ Punto de interacción con los usuarios finales. __Roles:__ Data Scientists, Data Analysts, UX/UI Designers, Software Engineers.