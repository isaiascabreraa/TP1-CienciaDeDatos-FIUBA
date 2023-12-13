# TP1-OrganizacionDeDatos
Primera parte - Visualización de Datos (6ptos)
Para esta primera parte, deberán realizar los siguientes plots:

Realizar tres visualizaciones que expliquen los datos del TP utilizando los siguientes tipos de plots:
Histograma (1pto)
Violin plot o Box plot (1pto)
Heatmap (1pto)
Realizar un plot sobre los datos, utilizando un tipo de plot que no sea ninguno de los usados en el punto uno, que permita mostrar el comportamiento o interacción de al menos tres variables. (3ptos)

Segunda parte - Pandas (8 ptos)
Realizar sus correspondientes consultas en Pandas:
1) Indicar el nombre y el tamaño de las aplicaciones educativas.
2) Mostrar el largo promedio de las reviews por tipo de sentimiento.
3) Utilizando los textos de las reviews, realizar una consulta mediante técnicas de NLP de modo que la query “love game” devuelva una app, especificando su nombre, rating y la review.
4) Para cada categoría, calcular cuál es el caracter predominante en la misma. El caracter predominante en una categoria esta dado por el caracter que es dominante en mayor número de apps, por ej para aaaaaaax, xxb, xxs el caracter dominante de ap1 es a, pero para las otras 2 x, por lo que x es el caracter dominante en la categoría. Si no hay caracter dominante, es el primer caracter.
5) Queremos saber cuánto pesaría si quisiéramos bajar todas las apps de un género, para todos los géneros. Para eso se pide: Calcular separado por géneros, cuanto pesarian todas las apps que tienen ese género y ademas, tener en cuenta que si una app tiene acción y arte, su peso cuenta para ambos géneros.

Tercera parte: Spark (8 ptos)
Realizar sus correspondientes consultas en Spark:
1) Obtenga la matriz de distancias en días entre fechas de actualización de las aplicaciones pagas. ¿Cuáles son las dos aplicaciones con mayor distancia?
2) Calcule el tamaño promedio de las aplicaciones por versión de Android, sin tener en cuenta las aplicaciones que varían en tamaño según dispositivo.
3) Para cada categoría, indicar cuál es la aplicación que tiene mayor cantidad de reviews con sentimiento negativo.
4) ¿Cuál es la aplicación con el nombre más largo?
5) Indicar el nombre y el tamaño de las aplicaciones educativas.
