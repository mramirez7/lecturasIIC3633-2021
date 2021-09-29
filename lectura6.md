# Deep Learning based Recommender System: A Survey and New Perspectives

El artículo comienza presentandose como un resumen de los últimos avances en el campo de sistemas recomendadores con deep learning (DL), inicialmente describe a 
grandes rasgos lo que son y lo que aportan los sistemas recomendadores y el boom que ha tenido el DL el último tiempo con grandes avances a nivel académico e industrial.
También se explica de donde es que han sacado sus fuentes para escribir el artículo. El enfoque principal es presentar distintas técnicas de DL que permiten capturar relaciones
usuario-item no triviales y no lineales para construir sistemas recomendadores más complejos.

El paper continúna describiendo diversas arquiecturas de manera general presentando ventajas y desventajas. En mi opinión las descripciones son buenas de manera introductoria,
pero para implementar estas me parece que faltaría más detalle o conocimiento previo, lo anterior no me parece malo ya que no es el objetivo del artículo.

En un momento del paper se dice que casi no existen razones para no incluir DL en sistemas recomendadores hoy en día, si embargo creo que no hubo demasiado énfasis en cuanto 
al costo temporal de entranamiento de mucho de estos modelos que en algunos casos me parece que puede ser un trade-off, por ejemplo, en ciertos escenarios recomendar no 
personalizadamente (ej: popularidad) podría ser una mejor opción por tiempo de entrenamiento e implementación (lo que aumenta su costo a nivel industrial).

En lo que sí estoy de acuerdo es cómo con buenas representaciones de datos la no linealidad que ofrece el DL permite llegar a resultados bastante buenos. Un aspecto negativo 
en el que también estoy de acuerdo es en la poca interpretabilidad de los resultados por la naturaleza de las redes neuronales y la dificultad de ajustar hiperparámetros de manera
correcta.

En resumen, creo que el paper cumple su propósito, ordena de manera clara las principales técnicas que combinan los dos mundos de sistemas recomendadores y DL. Lo clasificaría 
como un paper de nivel un poco más que introductorio ya que hay varios conceptos que nombra que son necesarios conocer de antemano.
