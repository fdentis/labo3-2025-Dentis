# Proyecto de Modelado Predictivo - Laboratorio III

Este repositorio contiene el trabajo final para la materia **Laboratorio III** de la Maestría en Ciencia de Datos.

El objetivo es predecir la variable objetivo a partir de un conjunto de datos (`sell-in.txt`), utilizando dos enfoques de aprendizaje automático automatizado (AutoML):

- **AutoGluon** 
- **H2O AutoML**

---

## Contenido del repositorio

- `autogluon_final.py`: Script de entrenamiento y evaluación con **AutoGluon**.
- `automl_por_producto.py`: Script de entrenamiento y evaluación con **H2O AutoML**.
- `Datos/`: Carpeta donde debe ubicarse el archivo `sell-in.txt`.
- `Salidas/`: Carpeta donde se guardan las predicciones.
- 
---

## ⚙️ Configuración del script de AutoGluon

El script `modelo_autogluon.py` está diseñado para permitir seleccionar **qué modelos ejecutar** modificando unas variables booleanas (`True` / `False`) al comienzo del archivo.
