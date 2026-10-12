# NovaRetail+ — Análisis de correlaciones del comportamiento del cliente

## Objetivo

Identificar qué comportamientos del cliente están más fuertemente
asociados con el ingreso anual generado para NovaRetail+, como apoyo
al equipo de Crecimiento y Retención.

El análisis es exploratorio y correlacional: no demuestra causalidad.

## Datos

El dataset contiene **15,000 registros y 12 columnas** sobre
características del cliente, actividad, publicidad, satisfacción,
membresía, abandono, dispositivo, región e ingreso generado.

La métrica principal es `ingreso_anual`.

Proyecto desarrollado como parte de la formación en análisis
de datos de TripleTen.

## Contenido del análisis

1. Carga y exploración del dataset.
2. Preparación de datos y documentación de supuestos.
3. Visualización de relaciones mediante heatmap y scatterplots.
4. Cálculo de Pearson, Spearman, punto-biserial y V de Cramér.
5. Interpretación de hallazgos e implicaciones de negocio.
6. Limitaciones y próximos pasos.

## Archivos del repositorio

| Archivo | Contenido |
|---|---|
| `Ecommerce_Correlational_Analysis.ipynb` | Código, visualizaciones, resultados y reporte de análisis. |
| `novaretail_comportamiento_clientes_2024.csv` | Dataset utilizado en el proyecto. |
| `README.md` | Descripción del proyecto e instrucciones de ejecución. |

## Herramientas

Python, pandas, NumPy, Seaborn, Matplotlib y SciPy.
Notebook ejecutado en Google Colab.

## Cómo reproducir el análisis en Google Colab

1. Descarga `novaretail_comportamiento_clientes_2024.csv`
   desde este repositorio.
2. Abre `Ecommerce_Correlational_Analysis.ipynb` y haz clic
   en **Open in Colab**.
3. En el panel **Archivos** de Colab, sube el CSV.
4. Comprueba que su ruta sea:
   `/content/novaretail_comportamiento_clientes_2024.csv`.
5. Ejecuta las celdas en orden, desde las importaciones
   hasta el último cálculo.

El notebook incluye resultados guardados para consultar el análisis
sin ejecutarlo. Para recalcularlos, es necesario cargar el CSV
en la sesión de Colab.
