# Desafio-Evaluacion-ML-Forte
Mejoramos el modelo de regresión logística de la entrega previa a través de Feature Engineering y agregamos medidas de evaluación del modelo.

#**Objetivos de la entrega**

En el desafío anterior evaluamos un modelo de regresión logística para predecir si una observación redunda en una venta o no.

Recordemos que una de nuestras variables, "order", toma el valor 1 cuando se trata de una venta y 0 caso contrario.

Vimos que un modelo simple y con una relativamente leve carga de Feature Engineering arrojaba un accuracy del 90%, lo cual habla de una estructura de datos adecuada para predecir ventas.  

En esta entrega vamos a profundizar y mejorar la aplicación de dicho modelo de regresión logística a través de los siguientes pasos:

> a) Feature Engineering: Aplicaremos Forward Selection, usando el accuracy como medida a optimizar, para quedarnos sólo con las variables explicativas relevantes a la hora de predecir ventas.

> b) Hypertuning de parámetros: Vamos a aplicar lo que aprendimos en las clases que transcurrieron desde la última entrega en materia de Grid Search, con el objetivo de tener los mejores parámetros para nuestra regresión logística.

>c) Una vez hecho esto, vamos a comparar los resultados del modelo con los de la entrega anterior, y vamos a agregar más formas de evaluar la eficacia del modelo, en función de lo que aprendimos en la clase 45, a la matriz de confusión, z-scores y el accuracy vamos a agregar precisión, sensibilidad, F1 Score y Curva ROC.


