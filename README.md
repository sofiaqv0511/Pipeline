# Pipeline
#### Elaborado por: Sofía Quiroz Valencia 
#### Ciencia de Datos II

#### Descripción
Este proyecto utiliza el Kidney Disease Dataset para realizar un análisis exploratorio de datos (Mini-EDA) y construir un pipeline de preprocesamiento. Se trabajan variables numéricas, categóricas nominales y ordinales, además del tratamiento de datos faltantes.

#### Resumen

El dataset contiene información clínica de pacientes y tiene como objetivo identificar si presentan o no enfermedad renal crónica (CKD). Para el análisis se seleccionaron variables relacionadas con la edad, presión arterial, glucosa, hemoglobina y diferentes indicadores clínicos.

El proyecto incluye la limpieza de datos, análisis de datos faltantes, clasificación de variables, imputación, escalamiento y codificación de variables categóricas mediante un pipeline de scikit-learn.

#### Contenido
- Mini-EDA: exploración inicial y descripción de las variables.
- Datos faltantes: identificación y estrategia de imputación.
- Variables numéricas: análisis de rangos y escalamiento.
- Variables categóricas nominales: identificación de categorías y One-Hot Encoding.
- Variables categóricas ordinales: identificación del orden y Ordinal Encoding.
- Custom Transformer: limpieza personalizada mediante FunctionTransformer.
- Pipeline de preprocesamiento: integración de todas las transformaciones mediante Pipeline y ColumnTransformer.
- Datos procesados: resultado final del preprocesamiento listo para utilizarse posteriormente en modelos de Machine Learning.
