# team_challenge2_grupo5
Team Challenge 2 - Grupo 5
En este repositiorio se enceuntramn los retos asociados al segundo tema challenge.
1- Para este ejercicio hay que ponerse la gabardina y el sombrero para investigar un asesinato en SQL City. 

Se deberan aplicar los conecoptos básicos de SQL y se tendrán que manejar con un modelo de datos, mientras se resuelve un caso de asesinato :)

Este espectacular juego está creado por Joon Park y Cathy He, y pose podran encontrar todos los detalles en http://mystery.knightlab.com.

Se tendrá que resolver el caso a través de la propia web, donde se encontrara un intérprete de sentencias SQL interactivo. Hay que apuntar las queries y su resultado y cuando se tenga el caso resuelto, deberá armar un notebook en el que atacando a la base de datos existente en el directorio data, se resuelva el crimen con las mismas queries de la página web. 

2- Diseñar el modelo de datos con las tablas SQL, sus campos y tipos, así como las relaciones de una base de datos cuyas características se detallan a continuación:
    Desde negocio nos indican que es necesario llevar un control de las piezas que nos suministra cada proveedor. Esto es de tremenda importancia para la trazabilidad y control de calidad de los diferentes componentes, por lo que es muy importante conocer la cantidad de las diferentes piezas que nos suministran nuestros proveedores y en qué fecha lo hacen, considerando que:
        - Un mismo proveedor puede suministrarnos la misma pieza en diferentes fechas (diferentes lotes o partidas).
        - Una misma pieza puede ser suministrada por diferentes proveedores.

    Dados estos requerimientos, decidimos diseñar una base de datos sobre proveedores para la que disponemos de la siguiente información:

    De cada proveedor conocemos:
        - Código de proveedor (único).
        - Nombre.
        - Dirección.
        - Ciudad.
        - Provincia.

    De cada pieza conocemos:
        - Código de pieza (único).
        - Nombre.
        - Color.
        - Precio.
        - Categoría (una pieza solo puede pertenecer a una categoría).

    De cada categoría conocemos:
        - Código de categoría (único).
        - Nombre.