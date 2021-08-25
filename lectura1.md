# Collaborative Filtering Recommender Systems

Me parece un artículo muy bueno como introducción al área de sistemas recomendadores, si bien tiene más de 30 páginas es muy fácil de leer. En primera instancia 
hace un breve paso histórico de CF que me pareció útil para dar contexto.

Luego de la introducción se muestran distintos objetivos que se pueden intentar lograr, este punto lo encontré interesante por que muestra ideas que yo no había pensado,
por ejemplo recomendar items a grupos completos o recomendar items repetidos como podría ser en el caso de qué comer. Se continúa definiendo algunos conceptos básicos útiles
y condiciones para que un sistema funcione correctamente, esta última parte también me hizo pensar en casos nuevos que antes del comienzo del curso no había pensado "qué pasa si
el ítem tenía un ciclo de vida y ya perdió interés general?", "cómo manejamos los cambios de gusto del usuario?". Si bien no se da respuesta inmediata invita a hacer 
reflexiones iniciales.

Se continua presentando dos grandes categorías de algoritmos, por un lado los algoritmos probabilísticos, donde se presentan métricas vistas en clases, como la 
correlación de Pearson y los algoritmos probabilísticos, basados en distribuciones probabilísticas como su nombre lo indica.

Después se presenta un _tradeoff_ bastante natural respecto a cómo recopilar los ratings de los ítems, en este punto se menciona que el usuario al puntuar explicitamente
un ítem reduce el error en comparación a si el rating es a partir del comportamiento del usuario. Personalmente creo que podrían haber excepciones, por ejemplo, alguna vez me
recomendaron una aplicación llamada _photofeeler_ en esta puntuabas fotos de otras personas para un uso determinado, por ejemplo, perfil de _linked in_ una vez hubieras puntuado
cierto número de fotos, tus fotos comenzaban a aparecerle a las personas y así el sistema te recomendaba tu foto ideal para el uso deseado. El problema que veía es que las
puntuaciones pese a ser explícitas tenían un sesgo importante por querer ser evaluado más rápido y también por cansancio (luego de evaluar 20 fotos creo que uno evalúa más a la
rápida). Por lo anterior pienso que no siempre la puntuación explícita va a ser mejor, hay que tener cuidado con otras variables que pueden influenciar al usuario.

Finalmente se habla de otros puntos como que no existe una manera mejor para medir el _accuracy_ del sistema lo cual es esperable, aspectos sobre seguridad y algunas preguntas
abiertas. Como comencé diciendo, me pareció un excelente artículo para adentrarse en sistemas colaborativos.
