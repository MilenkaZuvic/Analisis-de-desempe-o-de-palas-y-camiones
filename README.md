# Análisis de desempeño de palas y camiones

Este proyecto tiene como objetivo analizar la eficiencia operativa de 47 camiones CAEX y 4 palas en tareas de carga y transporte en minería. Se evaluaron métricas clave como la cantidad de material transportado, los ciclos de operación y las distancias recorridas, permitiendo identificar los factores críticos que afectan el desempeño de los equipos y proponer estrategias de optimización.

## Resumen del Análiis
* Exploración y Limpieza de Datos
Se eliminaron valores anómalos y registros inconsistentes, como los camiones CAEX60 y CAEX23, que presentaban valores de tonelaje igual a 0 debido a errores de registro. Además, mediante Isolation Forest y DBSCAN, se identificaron 14,673 valores atípicos, aunque no todos fueron eliminados por falta de información adicional.

* Clasificación de Desempeño
Se realizó un ranking basado en métricas normalizadas de eficiencia en carga y transporte. .

* Modelado Predictivo con Random Forest
Utilizando un modelo de Machine Learning, se identificaron los factores críticos que impactan el desempeño de los equipos.

## Requisitops Previos

* Python 3.x
* Librerias: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

