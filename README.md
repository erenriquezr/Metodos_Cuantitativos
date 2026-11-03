# Metodos_Cuantitativos
Repositorio del curso de métodos cuantitativos

# 1. Descripción del proyecto
El proyecto presenta el análisis cuantitativo teniendo en cuenta el dataset de respuestas sobre seguridad digital, para ello se ulizan téncias y métodos de análisis estadístico, que permitan identificar y caracterizar factores asociados a la seguridad digital.

# 2. Fuentes de información
* SurveyResponses_DigitalSecurityAroundTheWorld.csv, el cual consta de 12.351 registros y discriminando 248 variables.

De igual manera se tienen los documentos guía para apoyo de interpretación del datset que son:
* Problema-analitico-rector.md: Documento base del problema analítico para orientar el desarrollo del trabajo.
* DataMap_DigitalSecurityAroundTheWorld.pdf: Diccionario de variables y preguntas del dataset.

# 3. Organización del proyecto
Metodos_cuantitativos/
│
├── README.md
├── LICENSE
├── requirements.txt
│
├── data/
│   └── README.md
│   └── DataMap_DigitalSecurityAroundTheWorld.pdf
│   └── Problema-analitico-rector.md
│   └── SurveyResponses_DigitalSecurityAroundTheWorld.csv
│
└── notebook/
    ├── Fase2_MetodosCuantitativos_Fase2.ipynb
    └── README.md

* README.md: Archivo de generalidades sobre el proyecto
* LICENSE: Archivo con las condiciones de licenciamiento y uso del notebook.
* requirements.txt: Especificación de los requisitos a nivel de librerías.
* notebook/: Carpeta con el notebook del desarrollo del ejercicio.
* data/: Carpeta con las instrucciones y documentación relacionada con el dataset.

# 4. Instrucciones de ejecución
Clonar o descargar este repositorio.
Instalar Python y Jupyter Notebook.
Instalar las dependencias mediante:
pip install -r requirements.txt
Obtener el dataset original de acuerdo con las instrucciones y condiciones de acceso documentadas en la carpeta data/.
Ubicar el archivo CSV en la ruta de datos configurada en el notebook.
Abrir notebooks/Analisis_Cuantitativo_Fase2_AdrianaNoguera.ipynb.
Ejecutar las celdas en orden.
5. Dependencias
El análisis utiliza las siguientes librerías de Python:

pandas 3.0.3
numpy 2.4.6
matplotlib 3.11.0
seaborn 0.13.2
scipy 1.18.0
statsmodels 0.14.6
scikit-learn 1.9.0
jupyter 1.1.1
Las versiones se encuentran especificadas en requirements.txt.

6. Metodología de análisis
El desarrollo comprende el análisis exploratorio de los datos, la construcción de una variable objetivo de victimización digital, la preparación de los datos y la aplicación de tres modelos de clasificación:

Regresión logística.
Random Forest.
Gradient Boosting.
La evaluación contempla métricas de clasificación, validación cruzada y procedimientos estadísticos para comparar el desempeño de los modelos.

7. Resultados principales
En el conjunto de prueba, Gradient Boosting obtuvo el mayor valor de F1-score (0.7995), seguido de Random Forest (0.7626) y regresión logística (0.7134).

Las comparaciones mediante bootstrap pareado mostraron diferencias en F1-score entre los tres modelos, con intervalos de confianza del 95 % que no incluyeron el cero.

8. Limitaciones
Los resultados deben interpretarse considerando la presencia de registros incompletos, el carácter autorreportado de la información, el desequilibrio en la distribución de la variable objetivo y la ausencia de validación externa. Los modelos permiten identificar patrones predictivos, pero no establecer relaciones causales.

9. Autoría y licencia
Autora: Adriana del Pilar Noguera Torres
Proyecto: Análisis cuantitativo integral – Fase 2
Entorno: Python – Jupyter Notebook
Licencia del código: MIT.

La licencia MIT se aplica al código desarrollado para este proyecto y no modifica las condiciones de uso del dataset ni de los documentos originales.

10. Repositorio
Repositorio público
