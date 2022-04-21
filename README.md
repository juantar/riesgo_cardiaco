# Prediccion_Riesgo_Cardiaco
Proyecto creado para el curso Científico de Datos brindado por CoderHouse


# Introducción

![Corazon](https://user-images.githubusercontent.com/68995559/164550544-4cb8f05e-b6c6-4c23-9620-1a8bb963967b.jpg)

En 2019, las enfermedades cardiovasculares acabaron con la vida de casi 18 millones de personas, lo que representa el 32 % de las muertes en todo el mundo (Fuente: Organización Mundial de la Salud, 2021). El 85% de estas muertes se debieron a ataques cardíacos y accidentes cerebrovasculares, con un 38% entre personas menores de 70 años.

La detección temprana es fundamental en el tratamiento y manejo de enfermedades cardiovasculares, donde el aprendizaje automático puede ser una herramienta poderosa para detectar un posible diagnóstico de enfermedad cardíaca.

# Preguntas y objetivos de la investigación

El objetivo de la investigación es desarrollar un programa de aprendizaje automático capaz de detectar enfermedades cardíacas en temprana edad para pacientes de alto riesgo, tales como diabetes, hiperlipidemia o alguna enfermedad ya establecida.

Nuestra pregunta y desafío principal es si con una poca cantidad de datos relativamente fácil de medir, se puede obtener un modelo de predicción adecuado para prevenir enfermedades cardíacas.

El objetivo principal de este trabajo es poder desarrollar el modelo de predicción mencionado. Para tal fin, en principio, se analizará y preparará la base de datos disponible, la cual será el input del modelo. Luego, se probarán distintos modelos de clasificación y se seleccionará el modelo que ajusta mejor para la problemática que se pretende resolver.

# Data Acquisition

El dataset fue seleccionado de la página kaggle. El mismo cuenta con variables facilmente medibles en análisis de rutina que se pueden obetener en cualquier estudio cardíaco que se realice una persona en cualquier hospital de recursos moderados.

Fuente https://www.kaggle.com/fedesoriano/heart-failure-prediction

# Integrantes
Targize Juan Ignacio

Salvatori Guadalupe 

# Tabla de Contenidos del notebook:
   * [Empresa y Problema específico](#section_1_empresa)
   * [Preguntas y objetivos de la investigación](#section_1_preguntas)
   * [Conformación del equipo de trabajo](#section_1_equipo)
   * [Data Acquisition](#section_1_data_acquisition)
   * [Variable Description](#section_1_data_acquisition_variables)
   * [Data wrangling y EDA](#section_1_eda)  
       * [Análisis Variables Númericas](#section_1_eda_var_num)
       * [Análisis Variables Categóricas](#section_1_eda_var_cat)
       * [Correción de Datos y Outliers](#section_1_eda_outliers)
       * [Matriz de Correlación](#section_1_eda_matriz)
       * [Pair Plots](#section_1_eda_pair_plots)
   * [Preparación de datos](#section_2_preparacion_datos)
   * [Algoritmo de Clasificación](#section_2_algoritmos)
   * [Árboles de Decisión](#section_2_algoritmos_arboles).
   * [Random Forest](#section_2_algoritmos_random) 
   * [Regresión Logística](#section_2_algoritmos_reg_log) 
   * [Validación de datos](#section_3_valid_datos)
       * [Validación Simple](#section_3_valid_datos_simple)
       * [Cross validation: KFold](#section_3_valid_datos_Kfold)
       * [Cross Validation: Leave One Out](#section_3_valid_datos_leaveoneout)
       * [Comparación validaciones](#section_3_valid_datos_comparacion)
   * [Grid Search](#section_3_grid_search)
   * [Random Search](#section_3_random_search)



