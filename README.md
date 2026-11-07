# Metodos_Cuantitativos
Repositorio del curso de métodos cuantitativos

# Análisis de Percepciones y Prácticas de Seguridad Digital en 12 Países

## Descripción del Análisis
Repositorio científico que integra el análisis exploratorio, inferencial y de aprendizaje automático sobre factores humanos en ciberseguridad, enmarcado en la línea doctoral CRIC de la Universidad de Nacional Abierta y a Distancia - UNAD.

## Dataset Utilizado
* **Nombre:** Survey Responses_DigitalSecurityAroundTheWorld.csv
* **Muestra:** 12,351 participantes distribuidos en 12 países
* **Referencia:** Encuesta internacional sobre alfabetización digital, percepciones de riesgo y adopción de medidas protectoras.

## Instrucciones de Ejecución

## Desde Google Colab:
* Descargar el repositorio.
* Subir al drive de google el dataset con extensión .csv
* subir en colab el notebook mediante: Archivo --> Subir cuaderno y escoger el archivo Fase2_MetodosCuantitativos.ipynb
* Ejecutar el notebook completo

## Desde entorno local (Linux):
* Instalar Python y Jupyter Notebook.
* Instalar dependencias mediante la instrucción pip install -r requirements.txt
* Clonar el repositorio.
* Instalar las dependencias exactas: `pip install -r requirements.txt`
* Abrir el entorno Jupyter e iniciar el notebook ubicado en `/notebooks/Fase2Parte2.ipynb`.
* Reiniciar el kernel y ejecutar todas las celdas secuencialmente.

## Estructura del repositorio
```text 
/
├── README.md
├── requirements.txt
├── LICENCE.md
├── data/
│   └── SurveyResponses_DigitalSecurityAroundTheWorld.csv
└── notebooks/
    └── Fase2Parte2.ipynb
```
## Licencia y autoría
Código distribuido bajo licencia MIT

Autor: Edgar Rodrigo Enríquez Rosero
Proyecto: Métodos cuantitativos – Parte 2
Entorno: Google Colab/Python – Jupyter Notebook
Doctorado en T.I - UNAD  2026

## Metodología de análisis
Teniendo en cuenta el perfil al cual se orienta el proyecto de grado, se escogió la opción 2, relacionada con series temporales, sin embargo el dataset existente no puede ser valorado bajo estas técnicas y por lo tanto  aplicación de tres modelos de clasificación:

Regresión logística.
Random Forest.
Gradient Boosting.
La evaluación contempla métricas de clasificación, validación cruzada y procedimientos estadísticos para comparar el desempeño de los modelos.


