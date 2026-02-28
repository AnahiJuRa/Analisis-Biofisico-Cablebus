#  Impacto Bio-Físico de la Línea 4 del Cablebús en el Parque Juárez, Puebla

##  Descripción del Proyecto
Este repositorio contiene un análisis técnico independiente desarrollado desde la perspectiva de la **Física Aplicada y la Ciencia de Datos**. El objetivo es cuantificar, mediante teledetección satelital y modelos matemáticos, el impacto real de la remoción de arbolado maduro en el Parque Juárez debido a las obras de la Línea 4 del Cablebús.



##  Metodología y Modelos Físicos
El análisis se divide en cuatro pilares fundamentales de rigor científico:

1. **Teledetección (NDVI):** Cálculo del Índice de Vegetación de Diferencia Normalizada mediante imágenes de la misión **Landsat 9**.
2. **Termodinámica de Enfriamiento:** Cálculo de la potencia frigorífica perdida basándose en el **Calor Latente de Vaporización** ($L_v$) de la evapotranspiración.
3. **Hidrología Urbana:** Simulación del incremento en el caudal de escorrentía superficial mediante el **Método Racional** ($Q = CIA$).
4. **Alometría Forestal:** Modelado exponencial de la biomasa y secuestro de $CO_2$ para evaluar la viabilidad de la mitigación propuesta.

##  Hallazgos Clave
* **Salud Vegetal:** Se identificó un NDVI máximo de **0.73**, indicando un ecosistema maduro de alta eficiencia.
* **Déficit Ambiental:** Se proyecta un déficit inmediato del **15.7%** en servicios ambientales, irrecuperable a corto plazo mediante retoños.
* **Regulación Térmica:** La remoción de un ejemplar maduro equivale a la pérdida de una unidad de enfriamiento de **~11.5 kW**.
* **Riesgo Pluvial:** El cambio de coeficiente de escorrentía de 0.15 a 0.85 garantiza una saturación del drenaje local durante tormentas.

##  Requisitos Técnico-Científicos
Para replicar este análisis, se requiere un entorno de Python con las siguientes librerías:
* `rasterio`, `geopandas`, `shapely` (Análisis Geoespacial)
* `numpy`, `matplotlib` (Modelado Matemático y Visualización)

##  Estructura de Datos
Para mantener el repositorio ligero, no se incluyen los productos térmicos crudos de la NASA. Los datos pueden obtenerse en [USGS EarthExplorer](https://earthexplorer.usgs.gov/) bajo la colección **Landsat 9 Level-2**.
