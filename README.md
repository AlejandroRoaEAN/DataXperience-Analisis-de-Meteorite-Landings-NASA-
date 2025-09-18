# Análisis de Meteorite Landings (NASA)

Este repositorio contiene el código y los resultados de un proyecto de analítica de datos basado en el dataset público “Meteorite Landings” de la NASA. El objetivo es recorrer todo el ciclo de vida del análisis de datos —desde la exploración y limpieza hasta la visualización y el modelado predictivo— aplicado a registros de más de 45 000 meteoritos que han caído a la Tierra.

## Contenido

### Etapa 1: Exploración y limpieza
- Scripts y notebooks que cargan el archivo `Meteorite_Landings.csv`, examinan los tipos de variables, identifican valores nulos y outliers, y aplican reglas de limpieza (corrección de fechas fuera de rango, tratamiento de masas nulas o negativas y coordenadas inválidas).
- Se genera un fichero depurado `Meteorite_Landings_clean.csv` y un resumen de estadísticas básicas.

### Etapa 2: Análisis estadístico
- Cálculo de medidas de tendencia central (media, mediana, moda) y dispersión (rango, varianza, desviación estándar) para las variables numéricas.
- Comparación entre categorías (por ejemplo, meteoritos “Fell” vs. “Found”), identificación de outliers mediante el rango intercuartil y análisis de correlaciones.
- Visualizaciones descriptivas (histogramas, boxplots, matrices de correlación) con interpretaciones en lenguaje sencillo.

### Etapa 3: Visualizaciones, storytelling y modelado
- Gráficos más elaborados que muestran tendencias por década, ranking de clases de meteoritos y mapas de dispersión geográfica.
- Entrenamiento de un modelo de regresión lineal para predecir la masa a partir del año y las coordenadas, con evaluación de su desempeño y discusión de sus limitaciones.
- Propuesta de aplicación profesional: combinación de datos históricos, sensores y algoritmos de IA para predecir zonas de caída y diseñar robots de recolección.

## Cómo utilizar el repositorio
1. Descarga o clona este repositorio.
2. Abre el notebook de tu preferencia (`*.ipynb`) en Google Colab o Jupyter Notebook.
3. Sube el archivo original `Meteorite_Landings.csv` (o utiliza la versión limpia `Meteorite_Landings_clean.csv`) y sigue las celdas de cada etapa. Los notebooks están comentados y divididos en secciones para facilitar su comprensión.
4. Reproduce las visualizaciones y ajusta parámetros o preguntas de análisis según tus intereses.

## Licencia
El dataset original proviene de la NASA y está en dominio público. El código de este repositorio se publica bajo licencia MIT. Consulta el archivo `LICENSE` para más detalles.
