# Proyecto 1

En Costa Rica la localización de direcciones siempre ha resultado un problema complicado para la entrega de paquetes y servicios de comida express. Aún cuanto gran cantidad de casas no cuentan con una numeración predeterminada eso generalmente no pasa en los residenciales. Cada residencial cuenta con una serie de bloques (manzanas) y una numeración secuencial de las casas. Sin embargo, esta numeración estándar tampoco se usa mucho sobre todo por el hecho que generalmente no se conoce o no está registrada en mapas en línea.

El objetivo de este proyecto consiste en realizar la recopilación de información de interés general sobre un residencial determinado. De esta forma cada grupo de estudiantes seleccionará un residencial al que tengan acceso y realizarán la recolección de datos sobre la numeración de las casas y sobre información general sobre la infraestructura de esa zona.

## Digitación de terrenos

Se debe localizar un residencial de interés que cuente con numeración de sus casas, y luego se deberá digitalizar desde [geoson.io](https://geojson.io) cada uno de los lotes (terrenos) que conforman dicho residencial. Note que usted debe utilizar las facilidades que permite GRASS para generar polígonos a partir de líneas, y la identificación de errores de digitalización. También debe almacenar el número de casa para cada uno de los lotes, generalmente son de la forma número y letra por ejemplo: 4D, 10F ó 8C.

Debido a que las imágenes disponibles pueden ser de baja resolución se puede asumir que la gran mayoría de los lotes tendrán dimensiones similares y de dicha forma solo sería necesario conocer cuántas casas hay de cada lado del bloque. Note, sin embargo, que siempre será necesario realizar una visita de campo para identificar los códigos de los bloques y los números de casas.

Se debe seleccionar un residencial que cuente con al menos unas 60 casas y preferiblemente que las dimensiones de los lotes sean regulares.

## Información de infraestructura:

Utilizando las funcionalidades del sitio [OpenStreetMap](http://www.openstreetmap.org) se deben obtener los diferentes tipos de elementos existentes en dicho sitio y completar con información de infraestructura que debe levantarse desde el campo.

Los elementos tipo área que se deben incluir, entre otros, serían:

* Edificios: Iglesias, Escuelas, Hospitales, Bancos, Supermercados, etc.
* Canchas de deportes, canchas de tenis, parques, parqueos, etc.

Los elementos lineales incluirían, entre otros, los siguientes.

* Ríos, quebradas, etc.
* Líneas eléctricas primarias
* Senderos en parques recreativos

Los elementos puntuales incluirían, entre otros, los siguientes.

* Semáforos
* Postes eléctricos
* Hidrantes
* Torres de telefonía celular 
* Teléfonos públicos
* Paradas de autobuses

## Publicación de la información recolectada

Toda la información recolectada debe ser publicada a través de un mapa Web que quede publicado en un servicio de hosting tal como: Netlify, Vercel, Github Pages, GitLab Pages, ó Cloudflare Pages.

Dicho mapa puede ser desarrollado utilizando alguna librería de mapas Web tales como: Leaflet, OpenLayers, MapBox, ó Google Maps. El mapa Web debe mostrar e identificar cada lote del residencial, así como otra infraestructura principal (escuelas, parques, etc.). Otros elementos puntuales se deben mostrar mediante algún tipo de íconos adecuado. 

## Observaciones

* Para recolectar la información de campo (en la calle) deben de tomar todas las medidas de seguridad recomendadas.
* El proyecto debe ser realizado en grupos de dos estudiantes (de ninguna forma se permitirán grupos de tres o más estudiantes).
* Debe entregar un informe (en formato markdown) con la información de los elementos geográficos que se identificaron e ingresaron al sitio.
* El proyecto se debe entregar mediante un repositorio de Classroom de Github.
