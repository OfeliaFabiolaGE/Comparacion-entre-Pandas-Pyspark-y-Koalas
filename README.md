# Comparación entre Pandas de Python, Pyspark  y Koalas
INTRODUCCIÓN

En el repositorio se encontrarán 4 partes; la primera es el notebook que contiene la sintaxis usada en pandas y lleva por nombre Proyecto Parte1 Pandas, el segundo notebook lleva por nombre Proyecto Parte2 Pyspark y junto con este va el notebook de nombre Grafica pyspark, y la ultima parte es el notebook que lleva por nombre Proyecto Parte3 Koalas, cada uno contiene sintaxis de cada lenguaje respectivamente para así poder comparar la eficiencia entre los 3 por lo que a continuación colocare una "comparacion de comandos en el que coloco cual seria el lenguaje ganador en este apartado, posteriormente la comparación para graficar entre cada lenguaje y cual es el mas eficaz y al final la conclusión o perspectiva general:

COMPARACIÓN DE COMANDOS:

A pesar de que los tres lenguajes tienen similitudes con los comandos algunos hacen cosas diferentes que se puede notar al comparar los tres codigos, en este apartado gana Python seguido de Pyspark y al final Koalas.

Por ejemplo: 

Para consultar el total de filas y columnas tenemos lo siguiente en cada lenguaje:

![237758928-d9f65e15-c24a-478c-8f2e-2580cee909c9](https://github.com/OfeliaFabiolaGE/Parte2/assets/121463974/962afc5d-f746-4adb-8241-bc25c8516720)


Para obtener el tipo de dato de cada columna tenemos que Pyspark tiene dos maneras de mostrar los datos, mientras que python y pandas una sola:
![237755584-89bcc730-117b-453e-9f44-b49fba834043](https://github.com/OfeliaFabiolaGE/Parte2/assets/121463974/5ade17e7-11d2-415b-bda0-2ba1b1e9b9bc)

Para obtener un calculo "estadistico" pandas y koalas tienen el comando describe que hace algo parecido, en cambio Pyspark hace algo más largo como se puede ver en la imagen:

![237761355-90cfd507-edd6-442b-a264-9140a54ddef3](https://github.com/OfeliaFabiolaGE/Parte2/assets/121463974/6fc0a3e1-297d-4c54-90d2-a58db468318b)

![237762177-27ce51f6-8c64-47b7-899a-fcd755e3c027](https://github.com/OfeliaFabiolaGE/Parte2/assets/121463974/0636d74f-f00c-47c5-adb2-6904a36322e4)
![237762259-63da4345-e7a9-4e24-a748-5b01a3445f56](https://github.com/OfeliaFabiolaGE/Parte2/assets/121463974/d78e62a4-abcb-4f96-9d8d-cbcc5900febd)

En la parte de filtrado de filas y columnas tenemos que Pandas tiene dos opciones, la primera en la que solo filtra filas especificas y la que combina el filtrado de fila y columna tambien pudiendo hacerlo muy especifico, Pyspark tiene algo parecido, pero no tiene el comando .loc ni .iloc en cambio pandas si lo maneja, de la misma manera que maneja filtrado de columnas y filas combinadas y de forma especifica:
![237769374-e5917ff0-bf45-4f68-a9d3-3c9b4a52b803](https://github.com/OfeliaFabiolaGE/Parte2/assets/121463974/89be53aa-a919-476a-a027-c8af2fd13235)

![237773100-c9794bb1-ba7b-4fcb-98bc-1418d6d921ff](https://github.com/OfeliaFabiolaGE/Parte2/assets/121463974/425f1be9-9170-4962-a1bf-cb1ab504c4f3)


GRAFICAR

En esta parte yo pondria en primer lugar a mi gusto a Pandas de Pyton, en segundo lugar a Koalas y en tercer lugar a Pyspark, lo he hecho asi pues cuando use cada libreria de cada uno respectivamente pandas era facil de usar intuitivo y con muchas sintaxys faciles, koalas tiene su propia sintaxys, entendible a pesar de ser relativamente nuevo; pyspark al final pues en mi caso no se entiende muy bien su sintaxys.


PERSPECTIVA GENERAL:

El analisis fue hecho en un nivel basico de consulta en los tres lenguajes sin embargo el analisis completo se podria ver en casos mucho mas complejo con un dataset mas grande, se debe aclarar que tambien en esta consulta hubo resultados notorios en los que yo colocaria en el mejor a Pandas seguido de Koalas y en tercer lugar Pyspark lo coloco de esta forma por la facilidad y rapidez de cada lenguaje que note a la hora de realizar el codigo para cada uno, Koalas tiene potencial sin embargo aun le falta mas desarollo, en el futuro podria incluso estar entre los mas usados a la par que Pandas.
