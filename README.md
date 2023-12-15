# Modelo GAM para la Predicción de Resistencia Compresiva en Vigas de Concreto

## Descripción
Este proyecto utiliza modelos de Regresión Aditiva Generalizada (GAM) para predecir la capacidad de resistir fuerzas compresivas en vigas de concreto. Se realiza un análisis exploratorio de datos, se ajustan modelos GAM sin y con GridSearch, y se evalúa su rendimiento en términos de R^2, RMSE y Median Absolute Error. Además, se realiza un análisis de dependencia parcial para entender la relación entre las variables y la resistencia compresiva.

## Instrucciones de Uso
- Clona este repositorio en tu máquina local.
- Asegúrate de tener las dependencias instaladas ejecutando pip install -r requirements.txt.
- Ejecuta el notebook Jupyter Resistencia_Compresiva.ipynb para explorar el análisis y los modelos.

## Dependencias
- pandas
- matplotlib
- seaborn
- numpy
- pygam
- scikit-learn
- jupyter (para ejecutar el notebook)

## Estructura del Proyecto
- Resistencia_Compresiva.ipynb: Notebook principal con el código y análisis.
- compresive_strength_concrete.csv: Conjunto de datos utilizado.
- README.md: Documentación del proyecto.
- requirements.txt: Lista de dependencias y versiones.

## Conjunto de Datos
El conjunto de datos incluye información sobre la cantidad de cemento, escoria de alto horno, ceniza volante, agua, superplastificante, agregado grueso, agregado fino, edad y resistencia compresiva de vigas de concreto.

## Análisis Exploratorio de Datos (EDA)
Se realiza un análisis detallado, incluyendo visualizaciones sobre la distribución de variables y la relación entre las características y la resistencia compresiva.

## Modelos Utilizados
Se ajustan dos modelos GAM, uno sin GridSearch y otro con GridSearch, y se evalúan en términos de R^2, RMSE y Median Absolute Error.

## Resultados
Ambos modelos muestran un buen rendimiento en el conjunto de prueba, con un Pseudo R-Squared de aproximadamente 0.927. Se presenta una mejora marginal en la métrica Median Absolute Error al implementar GridSearch.

## Autor
Víctor Urra

## Agradecimientos
Agradezco a las bibliotecas de código abierto utilizadas.
