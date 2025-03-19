# TITULO DEL DESIGN DOC
Link: [Link a este design doc](#)

Author(s):isaaC_garcia
Status: [Draft]

Ultima actualización: 2025-03-08

## Contenido
- Goals
- Non-Goals
- Background
- Overview
- Detailed Design
  - Solucion 1
    - Frontend
    - Backend
  - Solucion 2
    - Frontend
    - Backend
- Consideraciones
- Métricas

## Links
https://www.freepublicapis.com/punkapi

## Objetivo
Se trata de un bot que ayude a definir el tipo de cerveza para una persona.
## Goals
Enseñar a las personas bebedoras de cerveza a definir las caracteristicas que le gustan en una cerveza.

## Non-Goals

Educar la cata en las caracteristicas gustativas en bebidas a base de la fermenta de la cebada.
## Background
Ayudar a las personas a definir un buen maridaje.


## Overview
Se trata de un bot que ayude a las persona a definir los sabores implícitos en una cerveza y definir sus características.
Es comun que una persona expresa de manera personal el gusto por algun tipo de cerveza sin conocer de manera tecnica cual
es el contenido de la misma, se trata de los ingretientes y algunos detalles de su elavoración.

 

## Detailed Design
Mi bot se conecta con una api en la cual se encuentra una base de datos que ayudará a definir ciertos aspectos en base a 
la elaboracion de la cerveza, sin embargo, sera necesario crear una api nueva para conectar con la api en uso y con telegram.

## Solución 1

Crear una interfax en el bot que sea muy intuitiva, integrar una api a través de un codigo que recoja la información del usuario 
y esta a su vez, conecte con la api que nos ayudará con la base de datos donde se contiene la información que necesitamos y de 
esta manera poder dar una respuesta al usuario final.

Para esto: 

Se creará un bot en telegram através de Botfather y se obtendra un token de acceso.
Se configurará un servidor para el bot.
Se debera conectar con la api de punk https://www.freepublicapis.com/punkapi
El flujo del bot sera a través de preguntas relacionadas con lo que el usuario desea o puede esperar de su bebida.




## Solucion 2



## Consideraciones
El metodo de comunicacion (escrito)
Manejo de las respuesta de la API.
Optimizacion de consultas.
Escalabilidad por el numero de usuarios.
Interfaz amigable.
Respuestas claras y breves.

## Métricas
Número de consultas