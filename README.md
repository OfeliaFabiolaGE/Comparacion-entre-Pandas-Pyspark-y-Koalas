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

Pyspark
![237773807-e669dd7e-79e8-4ef7-b409-839dd65fe66d](https://github.com/OfeliaFabiolaGE/Parte2/assets/121463974/59a6e139-dae3-4404-b47f-96c01e3346ae)

![237773865-24132634-78ab-4bfa-8235-28311e1fc1e8](https://github.com/OfeliaFabiolaGE/Parte2/assets/121463974/85d618fa-abe3-4fc7-b5e5-d0e14df5dfae)

![237773957-cc886e3f-067e-4236-a988-70dd81393184](https://github.com/OfeliaFabiolaGE/Parte2/assets/121463974/acddd96c-676c-44a7-a594-fec563117fa0)

GRAFICAR

En esta parte yo pondria en primer lugar a mi gusto a Pandas de Pyton, en segundo lugar a Koalas y en tercer lugar a Pyspark, lo he hecho asi pues cuando use cada libreria de cada uno respectivamente pandas era facil de usar intuitivo y con muchas sintaxys faciles, koalas tiene su propia sintaxys, entendible a pesar de ser relativamente nuevo; pyspark al final pues en mi caso no se entiende muy bien su sintaxys ademas como se puede notar en la segunda grafica los nombres de las columnas quedan amontonados haciendo que se vea feo.

Ahora veremos porque Pandas se lleva el premio en cuanto Graficar:

Pandas:
![237775266-73236b25-076b-4f8a-b07e-1aa63ee8fb1a](https://github.com/OfeliaFabiolaGE/Parte2/assets/121463974/18a52800-cef3-4545-b65c-a069df967f56)

![237776254-e45e5216-915f-410e-8318-0651580be21d](https://github.com/OfeliaFabiolaGE/Parte2/assets/121463974/6b9a36bd-61bf-44ac-a8a1-a9b5e11c4074)


Pyspark:

![237775637-7a1dd814-1657-4232-834d-12fcf767840a](https://github.com/OfeliaFabiolaGE/Parte2/assets/121463974/ffb18fe1-6ff2-4586-b511-83e7130e8d8b)
![237775677-1a540a86-869d-4e40-9268-0d801c77079b](https://github.com/OfeliaFabiolaGE/Parte2/assets/121463974/96d9615e-967b-47cb-929c-b97e1caf5f86)

![237775738-f59318f6-4c0e-418d-9c24-4e28c671b706](https://github.com/OfeliaFabiolaGE/Parte2/assets/121463974/92e9c896-42b3-432a-ac95-5aba91cae752)
![237775771-ab127eb8-433b-4741-aaaf-04a3b0e741f0](https://github.com/OfeliaFabiolaGE/Parte2/assets/121463974/24750f2f-d953-4e21-89a7-0cb4fc33dd6d)


Koalas:

![237784923-ba4cc322-1cd2-4cb5-9d17-8e5519cd2939](https://github.com/OfeliaFabiolaGE/Parte2/assets/121463974/3c097a8c-6c86-4a96-bc66-6f1f5be7ff07)

![image](https://github.com/OfeliaFabiolaGE/Parte2/assets/121463974/42de8be7-438b-413e-b880-a2f449407a26)


PERSPECTIVA GENERAL:

El analisis fue hecho en un nivel basico de consulta en los tres lenguajes sin embargo el analisis completo se podria ver en casos mucho mas complejo con un dataset mas grande, se debe aclarar que tambien en esta consulta hubo resultados notorios en los que yo colocaria en el mejor a Pandas seguido de Koalas y en tercer lugar Pyspark lo coloco de esta forma por la facilidad y rapidez de cada lenguaje que note a la hora de realizar el codigo para cada uno, Koalas tiene potencial sin embargo aun le falta mas desarollo, en el futuro podria incluso estar entre los mas usados a la par que Pandas.
