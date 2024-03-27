# Heart-disease

Apply and demonstrate all processes as "data analysis technicians" in analyzing the "heart.csv" dataset. To achieve this goal, it's important to select the most appropriate processes and conduct a thorough data analysis.

The main objective of this report is to apply and demonstrate all processes as "data analysis technicians" in the analysis of the "heart.csv" dataset. To accomplish this goal, it's important to select the most suitable processes to implement and conduct a correct data analysis.

Therefore, the partial objectives proposed to achieve the final goal are as follows:
1. Data analysis: initial manipulation and file preparation.
2. Information cleaning and description improvement (detailing the dataset's general meaning and its columns) using Python.
3. Creation of a Data Warehouse with MySQL (any enhancements to the database such as creating new tables, etc., will be appreciated).
4. Perform SQL queries displaying relevant information from our dataset.
5. Export data directly from MySQL to Pandas.
6. Implement possible improvements and transformations with PDI Spoon.
7. Perform analysis of all data using statistical methods.
8. Conclude and predict possible heart conditions based on the parameters studied after our data analysis. This will involve creating a linear regression model through training with "Scikit-learn".
9. Determine if reliable predictions of heart conditions can be made based on the input data.

In this case, a consolidated predictive model will not be used. Instead, the data will be analyzed through the complete process explained above. The "heart.csv" dataset includes the following parameters or fields:
- Age - age (in years).
- Sex - gender (1= males, 0 = females)
- cp - chest pain type (0: asymptomatic, 1: atypical angina, 2: non-anginal pain, 3: typical angina).
- trestbps - resting blood pressure (measured in mmHg).
- chol - serum cholesterol (in mg/dl).
- fps - fasting blood sugar (exceeds 120 mg/dl? - 0=no, 1= yes).
- restecg - resting electrocardiogram (ECG) (0: showing probable or definitive left ventricular hypertrophy according to Estes criteria, 1: normal, 2: with abnormal ST-T wave).
- thalach - maximum heart rate achieved.
- exang - exercise induced angina? (1=yes, 0=no).
- oldpeak - exercise-induced ST depression relative to rest.
- slope - slope of the peak exercise ST segment (0: downsloping, 1: flat, 2: upsloping).
- ca - number of major vessels (0–3).
- thal – Thalassemia (1 = normal, 2 = fixed defect, 3 = reversible defect).
- Target – target variable (1 = with heart disease, 0 = without heart disease).

CARDIOPATÍAS 
Aplicar y mostrar todos los procesos a realizar como “técnicos de análisis de datos” en el análisis del dataset “heart.csv”. Para cumplir este objetivo será importante seleccionar los procesos más indicados a implementar, así como realizar un análisis de los datos correcto. 

El objetivo principal de este informe es aplicar y mostrar todos los procesos a realizar como “técnicos de análisis de datos” en el análisis del dataset “heart.csv”. Para cumplir este objetivo será importante seleccionar los procesos más indicados a implementar, así como realizar un análisis de los datos correcto. 
Así pues, los objetivos parciales, que se proponen para alcanzar el objetivo final son los siguientes: 
1.	Analizar los datos: manipulación inicial y preparación del fichero.
2.	Limpieza de la información y mejora de las descripciones (detallando qué significa el dataset en general y sus columnas) utilizando Python.
3.	Creación de un Data Warehouse con MySQL (se valorará cualquier mejora que se pueda aplicar a la base de datos como la posible creación de tablas nuevas, etc.).
4.	Realizar consultas en SQL que muestren información relevante de nuestro dataset.
5.	Exportar los datos directamente de MySQL a Pandas. 
6.	Realizar posibles mejoras y transformaciones con PDI Spoon.
7.	Realizar el análisis de todos los datos aplicando métodos estadísticos.
8.	Concluir y predecir posibles cardiopatías en función de los parámetros estudiados tras nuestro análisis de los datos. Para ello habrá que realizar un modelo de regresión lineal mediante su entrenamiento con “Scikit-learn”.
9.	Determinar si con los datos de entrada se podrá obtener un modelo que ayude a predecir de forma fiable la probabilidad de padecer una cardiopatía.


En el caso que nos ocupa no se va a utilizar un modelo predictivo ya consolidado, sino que se van a analizar los datos mediante el proceso completo explicado en el punto anterior. El dataset – “heart.csv” presenta los siguientes parámetros o campos:
-	Age - edad (en años).
-	Sex - sexo (1= hombres, 0 = mujeres) 
-	cp - tipo de dolor de pecho (0: asintomático, 1: angina atípica, 2: dolor no anginoso, 3: angina típica).
-	trestbps - presión arterial en reposo (medida en mm/hg).
-	chol - colesterol sérico (en mg/dl).
-	fps - glucemia en ayunas (¿supera los 120 mg/dl? – 0=no, 1= sí).
-	restecg - electrocardiograma (ECG) en reposo (0: mostrando hipertrofia ventricular izquierda probable o definitiva según los criterios de Estes, 1: normal, 2: con onda ST-T anormal).
-	thalach - frecuencia cardíaca máxima alcanzada.
-	exang - ¿angina inducida por ejercicio? (1=si, 0=no).
-	oldpeak - depresión del S-T inducida por el ejercicio en relación con el reposo.
-	slope - pendiente del segmento S-T del ejercicio máximo (0: pendiente descendente; 1: plano; 2: pendiente ascendente).
-	ca - número de vasos mayores (0–3).
-	thal – Talasemia (1 = normal, 2 = defecto fijo, 3 = defecto reversible).
-	Target – variable objetivo (1 = con una cardiopatía, 0 = sin una cardiopatía).

