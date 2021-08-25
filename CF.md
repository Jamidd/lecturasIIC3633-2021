# CF RecSys

Este artículo presenta una muy buena introducción a la lógica detrás de los modelos de collaborative filtering. Explica desde las motivaciones históricas detrás de su inicial desarrollo, hasta ideas de implementaciones y modelos más modernos. 

También se habla de los diferentes tipos de usuarios, datos y las diferentes "queries" que podrían ser útiles para estos. En esta parte hablan bastante de la diferencia entre hacer una recomendación y una predicción. La verdad no había pensado mucho en este aspecto, pero me sorprendió las sutilezas que existen entre uno y otro. 

Además, comentan sobre la diferencia entre collaborative vs content based filtering. Donde el primero usa los gustos de las personas, mientras el segundo usa las características objetivas de cada elemento.

A continuación, seguimos revisando los diferentes tipos de modelos de CF. Donde por un lado tenemos probabilísticos y por el otro no probabilísticos. Estos existen debido al esperado trade-off entre tiempo-espacio-accuracy. Muchas veces no es posible ni práctico usar todos los datos recolectados para hacer una recomendación, o a veces necesitamos gran precisión. Diferentes tipos tienen sus pros y contras. 

Uno de los detalles, ya que no quiero decir problema, es el uso de variables continuas o discretas con muchas opciones, ya que en general se basan en comparar personas con personas o items con ítems, el problema se complica un cacho.

Otro de los aspectos importantes mencionados posteriormente son los problemas que podemos tener en estos algoritmos en el mundo real. Como cuando tenemos un nuevo ítem, un nuevo cliente, los ratings en general son sparce, y lo más importante (IMO), problemas de privacidad de los usuarios. 

Finalmente, termina con algunos problemas abiertos y resultados de implementaciones de CF. 

En general un muy buen artículo introductorio, muy fácil de leer, y con una buena estructura. 

