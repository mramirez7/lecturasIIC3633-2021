# Content-Based Recommendation Systems

El artículo busca mostrar un método de recomendación de ítems a partir de la descripción de estos para un perfil de usuario.

El artículo comienza dando ejemplos de data no estructurada y sus complicaciones evidentes que acompañan al lenguaje natural. Concuerdo con que existen hoy en día modelos de AI
que son capaces de lidear con clasificaciones de datos estructurados donde se saben los nombres de los atributos y sus valores, en varios casos. Por lo anterior es necesario buscar 
representaciones para campos non estructurados. Se evalua la opción de derivar palabras, juntando palabras conjugadas de manera diferente pero escencialmente iguales, el proble de
lo anterior es que muchas veces una palabra por sí sola no da suficiente información del contexto global, por lo que se sugiere usar grupos de palabras seguidas en vez de la 
palabra por sí sola.

En relación al perfil del usuario hay dos grandes formas de guardarlo, cómo una función que calcule un puntaje sobré qué tan probable es que le guste cierto ítem al usuario,
o como un historial de interacciones del usuario con el sistema que permita extraer información según su comportamiento. Me pareció muy interesante la parte que se habla sobre
los contras de pedirle al usuario que genere su propia información sobre sus gustos, ya que es particularmente difícil saber qué tan dispuesto está a dar esa información, a
tomarse el tiempo, calcular y priorizar preguntas, y además estar constantemente pendiente de actualizar su información personal en caso de cambio de gustos o descubrimiento
de gustos nuevos.

El artículo muestra luego técnicas de clasificación, personalmente las conocía o tenía una buena idea de como funcionaban casi todas a grandes rasgos, las dudas que me surgen de
los métodos es qué tan caro se puede volver en términos de complejidad computacional generar un modelo por cada usuario en sistemas de recomendación grandes donde se hacen actualizaciones
constantemente según el nuevo feedback del usuario.

Finalmente me parece que es importante lograr juntar los datos no estructurados con estructurados para tener sistemas más robustos en el futuro. Creo que uno de los
principales problemas que existen actualmente es la manera de representar datos no estructurados, yo me imagino que sería interesante probar modelos de deep learning para esto,
tal vez una red RNN pueda aportar más a nivel de contexto y no sería demasiado caro en tiempo ya que podría ser un modelo compartido entre todos los usuarios.
