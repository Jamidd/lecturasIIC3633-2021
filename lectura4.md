#Content Based RecSys

Este es más que nada un paper educacional, no presenta ningún resultado nuevo. El paper parte hablando de cómo representar información, más que nada textos, para lo cual menciona la representación tf*idf, la cual es esencialmente un bag of words con puntaje, donde para cada palabra este sube si la frecuencia de esta aumenta en varios textos y disminuye si esta está presente en muchos textos. Estamos buscando palabras que aparecen mucho en un texto pero en pocos textos. 

Después se menciona cómo aprender perfiles de usuario y por qué estos son importantes. La idea, es poder tener un vector que logre describir al usuario, lo que le gusta, lo que no le gusta y para esto se puede obtener información explícita cómo likes o implícita como que libros compro, que link pincho o qué música escucho. 

A continuación se pone a enumerar diferentes clasificadores DT, KNN, Rocchio’s Algorithm, Linear Class y Bayes. Los cuales no vale la pena ahondar ya que son mega conocidos.

Finalmente, termina hablando de que debido a la cantidad de datos de la World Wide Web, ML puede generar modelos de usuario de información no estructurada (big surprise face). Además, menciona los problemas que tiene Content Bases RecSys. Si tenemos datos que no están intrínsecamente estructurados, entonces estos sistemas no funcionan muy bien, como por ejemplo poemas o chistes, no tenemos una forma de generar una distinción significativa entre un chiste bueno y otro malo. Puede ser que a alguien le gusto un chiste de dentistas debido a que el chiste era bueno, y no necesariamente por que le gustan todos los chistes de dentistas. Por otro lado, películas o restaurantes son más fáciles de caracterizar y diferenciar, el tipo de cocina o el género de la película, son grandes indicadores de cada uno.

