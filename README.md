# Pipeline
#### Elaborado por: Sofía Quiroz Valencia 
#### Ciencia de Datos II

#### Descripción
Este proyecto se desarrolla utilizando el Kidney Disease Dataset, un conjunto de datos que contiene información clínica y de laboratorio de pacientes, con el propósito de analizar diferentes características relacionadas con la enfermedad renal crónica (Chronic Kidney Disease - CKD).
El trabajo se centra inicialmente en realizar un Mini-EDA (Exploratory Data Analysis) para conocer la estructura del dataset, identificar los tipos de variables, analizar los datos faltantes, revisar los rangos de las variables numéricas e identificar las categorías presentes en las variables categóricas.
Posteriormente, se construye un pipeline de preprocesamiento que permite aplicar diferentes transformaciones dependiendo del tipo de variable. También se incorpora un Custom Transformer mediante FunctionTransformer para realizar una limpieza inicial de los datos.

#### Resumen
El dataset tiene como variable objetivo classification, que permite identificar si un paciente presenta enfermedad renal crónica (ckd) o no (notckd). Para este proyecto se seleccionaron ocho variables predictoras: age, bp, bgr, hemo, rbc, htn, al y su.
Las variables seleccionadas se clasifican en numéricas, categóricas nominales y categóricas ordinales. Durante el Mini-EDA se identificaron valores faltantes en diferentes variables, por lo que se establecieron estrategias de imputación según el tipo de dato.
Finalmente, el pipeline integra la imputación de datos faltantes, el escalamiento de variables numéricas, la codificación de variables nominales y ordinales, además de una etapa de limpieza personalizada. El objetivo es obtener los datos correctamente transformados y preparados para su posible utilización en modelos de Machine Learning.

#### Contenido
- Mini-EDA: exploración inicial y descripción de las variables.
- Datos faltantes: identificación y estrategia de imputación.
- Variables numéricas: análisis de rangos y escalamiento.
- Variables categóricas nominales: identificación de categorías y One-Hot Encoding.
- Variables categóricas ordinales: identificación del orden y Ordinal Encoding.
- Custom Transformer: limpieza personalizada mediante FunctionTransformer.
- Pipeline de preprocesamiento: integración de todas las transformaciones mediante Pipeline y ColumnTransformer.
- Datos procesados: resultado final del preprocesamiento listo para utilizarse posteriormente en modelos de Machine Learning.
