# Eliscraper

### Web Scraper basico v1.0.3 (con fines educativos)

## :eyes:	Que narices es esto?
Se trata de un web scraper muy basico con el que pretendo obtener precios de articulos en webs comerciales.

## :detective: Como funciona?
El script se alimenta de unos ficheros de instrucciones modelados en JSON denominados "recetas".
Estos ficheros, contienen información de como obtener los distintos elementos que deseamos obtener.
Una vez se obtienen los datos vía cURL, estos son procesados a través de las indicaciones de la receta seleccionada y son dejados en un fichero CSV.

Para ejecutarlo, tan solo necesitas hacer `php main.php` y te saldrá un fichero CSV con los datos.

## :man_facepalming: Y lo has hecho en PHP? En serio?
Si, puesto que es el lenguaje que practicamente mas domino y me parece mas facil de trabajar, me ha parecido adecuado.

No obstante, ya teniendo el conocimiento del algoritmo, valoro el hacerlo con otros lenguajes, como Python, que posiblemente pueda ser mas eficaz y sencillo aún.

Pero esto es lo que hay, está hecho en PHP y listo

## :shrug: Y se quedará así?
Nooo, ni en broma. Pretendo ir mejorandolo poco a poco, mejorar rendimiento, permitir mas opciones, añadir mas recetas y salidas en distintos formatos y porque no, incluso hacer una interfaz grafica.

## :massage_woman:	Lo puedo utilizar?
Siempre que se cumpla la licencia y no se use para algo ilegal, puedes hacer lo que te de la gana, esto lo estoy haciendo para aprender.

## :toolbox:	Cambios

### 1.0.3 (Quique San Francisco)
- Se añade control de información de salida de trabajo.
- Se incrementa la seguridad de la aplicación, evitando excepciones.
- Se corrige el flujo de ejecución.
- Se añade una ayuda efectiva.

### 1.0.2
- Se modifica el README.md para añadir los cambios.
- La salida que se genera ahora informa de como se progresa.
- Se ha añadido un fichero de funciones y otro de output.
- Se añade fichero de configuración para poder modelar el comportamiento de la aplicación sin tocar el script.
- Se permiten entrada de parámetros.
- Se reestructura la aplicación para tener mas ordenado todo.

## :construction: Proximas mejoras
- Añadir salida interactiva
- Añadir conexión a Base de Datos.
- Adición de mas recetas.
- Añadir mejoras de la conexión y obtención de datos vía cURL.

## :bulb: TODOs
- Selección de idioma.
- API.
- Posibilidad de corregir fallos en linea.
- Valorar el usar otro lenguaje de programación mas efectivo (Python, .NET Core)
- Filtros de la propia receta indicados por parámetros.
