# Análisis_Datos_Steam
![alt text](https://sm.ign.com/ign_es/screenshot/default/steam7_xexd.jpg)

# Problema
Steam es una plataforma de distribución digital de videojuegos desarrollada por Valve Corporation, con mas 30000 juegos publicados.
Donde se analizaremos los siguientes temas:
* Lista de las compañías con mas videojuegos desarrollados.
* Clasificación de juegos por: Idioma, Edad requerida, Gratuitos o de forma de pago
* Géneros(videojuegos) mas consumidos en steam
![alt text](http://lambdageneration.com/wp-content/uploads/2014/10/steam-db-spotlight-865x405.jpg)

Para contribuir a este proposito, se realizo un dashboard de visualización de datos.
# Datos
Los datos que se utilizará para el analisis se encuentran en:
https://www.kaggle.com/datasets/nikdavis/steam-store-games?resource=download&select=steam.csv
* name= título del juego
* release_date= fecha de lanzamiento del juego
* platform= sistema operativo y disponibilidad de VR
* developer= empresas que crean y desarrollan el juego
* publisher= empresas que publican el juego
* overall_reviews= categorías generales de reseñas (positivas, negativas, etc.)
* tags= etiquetas populares asignadas al juego, incluido el géneros del juego
* rating= debería ser calificado por pegi pero
* language= idioma soportado por el juego
* genre = género del juego
* price = precio del juego
![imagen_Datos](https://user-images.githubusercontent.com/106397567/186097688-3c614c90-6a5d-4add-a66b-6530cb3ffdfe.jpg)
# Analisis de datos
* Compañías con mas videojuegos desarrollados:
![Analisis1](https://user-images.githubusercontent.com/106397567/186149467-a0fba29f-b4a1-4e4e-b77e-ca34bb6ffe77.jpg)

Se puede lograr ver que la compania que logro desarrollar mas juegos es Choise of Games con unos 94 juegos desarrollados.
Tambien se visualiza que la compania que publica mas juegos es Big Fish Games con unos 212 juegos publicados en steam.

* Clasificación de juegos por: Idioma, Edad requerida, Si son de pago o son gratuitos:
![analisis2](https://user-images.githubusercontent.com/106397567/186151620-892c1fa9-391c-4441-b25c-6a93a1d98378.jpg)

Se puede visualizar que el 98% de los juegos son publicados en idioma INGLES, mientras que un 2% presentan otros idiomas.
Se visualiza que hay una gran cantidad de videojuegos que son de pago siendo unos 24515 videojuegos, mientras que los videojuegos que son gratuitos abarca apenas los 2560
Muchos de estos videojuegos presentan requerimiento de edad, puede que tenga una edad especifica o uqe no present un limite de edad.

* Videojuegos mas consumidos por género:
![analisis3](https://user-images.githubusercontent.com/106397567/186166116-ffcfd319-b6c1-4776-945b-cb94edfcf625.jpg)

Hay una gran cantidad de videojuegos en el cual muchos usuarios utilizan a diario. El género con horas mas consumidas es el de Accion, Roles

# Conclusiones
* Tras el análisis llegamos a la conclusión que los juegos mas jugados en steam son de genero "rol por jugador" con el cual nos atrevemos a decir que cualquier juego que desarrollemos y sea de este genero podría llegar a ser exitoso en steam a comparacion a cualquier otro juego de otro genero
* También se pudo observar que en el año 2020 donde se propago la pandemia fue el año donde se desarrollaron aun mas videojuegos en steam esto debido al confinamiento y a la vez esto genero un crecimiento gradual de usuarios en steam. En total se lanzo un total de 9279 nuevos videojuegos esto en el año 2020.
