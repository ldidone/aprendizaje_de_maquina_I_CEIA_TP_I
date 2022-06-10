# Aprendizaje de maquina I CEIA - TP I: Detección de fraudes.

Repositorio de código para el TP 1 del curso de aprendizaje de máquina 1, de la CEIA - FIUBA sobre detección de fraudes.

## Indice de archivos:

- [1. EDA and Baseline Model.ipynb](https://github.com/ldidone/aprendizaje_de_maquina_I_CEIA_TP_I/blob/main/1.%20EDA%20and%20Baseline%20Model.ipynb): Aquí encontrará análisis exploratorio de los datos básico con el objetivo de comprender el problema planteado. Además, se propone un flujo de pre-procesamiento de los datos. Finalmente, se entrena un modelo simple (regresión logística), empleando tres estrategias para mitigar el desbalance de los datos: undersampling, oversampling y class-weighting. El objetivo de entrenar este modelo simple con estas estrategias, es poder establecer un baseline contra el que comparar modelos más complejos.
- [2. Experimentation.ipynb](https://github.com/ldidone/aprendizaje_de_maquina_I_CEIA_TP_I/blob/main/2.%20Experimentation.ipynb): Aquí encontrará diferentes experimentos empleando los siguientes modelos: Decision Tree, Random Forest y Linear SVC. Se concluye que el que mejor performa bajo la métrica F1-Score es el Decision Tree.
- [3. Best Model - Decision Tree.ipynb](https://github.com/ldidone/aprendizaje_de_maquina_I_CEIA_TP_I/blob/main/3.%20Best%20Model%20-%20Decision%20Tree.ipynb): Aquí se experimenta con diferentes parámetros sobre el modelo de Decision Tree con el objetivo de incrementar la performance del mismo. Finalmente se obtiene un modelo que arroja resultados muy positivos para el problema en planteado de detección de fraudes.

> Alumno: Lucas C. Didone
