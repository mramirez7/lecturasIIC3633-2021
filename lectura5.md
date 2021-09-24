# Combining predictions for accuarate recommender systems

Pese a ser un paper no tan largo me parece que no es fácil de leer por su alto uso de expresiones matemáticas y técnicas, más allá de eso me pareció interesante.
A grandes rasgos el paper busca mostrar como construir ensambles de sistemas recomendadores para la base de datos del Netflix Price. Se usaron principalmente 
5 algoritmos de filtrado colaborativo: : SVD, Neighborhood Based Approaches, Restricted Boltzmann Machine, Asymmetric Factor Model y Global Effects.

Inicialmente se explica como fue dividido el dataset para poder testear correctamente los experimentos. A continuación se muestran los principales modelos que fueron parte del
challenge describiéndolos individualmente. Finalmente se detalla como hacer el blending, explicando métodos de regresión lineal con ciertas modificaciones.

Algo que me gustó del paper, o más bien del dataset escogido, es que los datos son reales y de un volumen considerable, por lo que todo lo detallado es realmente aplicable 
con un impacto en el usuario. Finalmente me quedo con la sensación que hay algo de "arte" en combinar distintos modelos y mejorarlos, creo que al haber tantas opciones y
parametros que sincronizar la experiencia e intuición juega un rol importante para reducir esto a una cantidad de experimentos que sean capaz de ejecutarse y comparar para 
así llegar a un modelo que se acerque al óptimo.
