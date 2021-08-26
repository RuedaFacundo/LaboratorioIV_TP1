# LABORATORIO IV - TP 1

Primer trabajo practico de laboratorio IV - UTN Mar del Plata

**EJERCICIO 1:** 

Generar un archivo HTML 5 cuyo nombre será index.
Este deberá tener: head, body, header, nav y footer.


**EJERCICIO 2:**

Crear el head con el contenido indicado a continuación (Podés agregar otras etiquetas de prueba si querés):

Debe tener el siguiente título:

   <title>
       LABORATORIO IV 2019
   </title>

Se deben definir los colores de los encabezados h1, h2 y h3 con los colores que deseen
   <style>
       h1 {
           color: rgb(59, 18, 3)
       }

   </style>
   
**EJERCICIO 3:**

-	Crear el header con lo siguiente:
  - debe haber un encabezado de tipo h2 con el siguiente texto “BIENVENIDOS A LABORATORIO IV”

- Crear el nav con lo siguiente:
  - Generar un texto destacado con la etiqueta strong que diga: Software necesario para trabajar en esta materia
  - Una lista  con los dos link que nos redirigen a las páginas de xampp y wampp

<a href="http://www.wampserver.com/en/"> WAMP</a>

**EJERCICIO 4:**

Generar el body con el siguiente contenido:

- Generar un párrafo destacado (pueden usar strong) que diga:
“A continuación veremos algunos temas a tener en cuenta a la hora de crear una aplicación web.”

- Luego un encabezado con <h1> que diga: 
“Etiqueta h1”

- Seguido de otro párrafo que diga: 
“H1 es una etiqueta que sirve para colocar la frase que indica el título del contenido de una página web. Importante en este punto delimitar de forma clara la diferencia entre sitio web y página web: un título H1 debe hacer referencia a una página de tu sitio web, y no al sitio web en general.”

- Luego se debe crear una lista desordenada que contenga los siguientes ítems:
  1.  Si el titular H1 resume en una frase el contenido de la página actual, no tiene sentido que en un mismo documento web tengamos varios H1, pues el resumen de tu sitio debe ser uno. Un caso de mal uso relacionado con este hecho son los blogs donde en el listado de los últimos posts cada uno de ellos lleva un titular H1: esto no es correcto, y lo adecuado sería que en el listado los títulos fueran H2 (etiqueta de título de menor importancia), y al acceder al post completo ya sí se nos mostrará el título como un H1.

  2.	Si resume el contenido de una única página, tu sitio web completo deberá tener un H1 para cada uno de los documentos, que resuma el contenido de la misma de la forma más específica posible. Un caso de mal uso para esta norma son aquellos sitios web donde el H1 está dedicado en todas las páginas al nombre de la compañía.

  3.	Como título qué es, y estando el SEO (es la optimización para que tu sitio web salga orgánicamente, de forma no paga, dentro de los primeros resultados en buscadores como Google o Yahoo!) orientado en el fondo al usuario, lo lógico es que tu titular H1 aparezca cuanto más arriba de la página mejor, tal cual lo haría el título de una noticia en una web. Google confiere mayor importancia al contenido situado en el primer tramo de un documento web,y también para el usuario es  lógico encontrar el H1 en esa posición.

  4.	Un H1 no debería en principio ir enlazado a otros documentos, pues su contenido debería ser  importante únicamente para el documento que estamos viendo. Si colocamos un enlace en ese H1, vamos a indicar inconscientemente que la pagina importante para ese titulo es a la que enlazamos, y no la página actual. Desde otros documentos, esta pagina deberia estar enlazada con el mismo texto del H1 para reforzar la importancia de su titular, o variaciones de sus palabras clave para tratar de posicionar en varios términos relacionados.

  5.	El H1 debe mantenerse corto, pues la importancia de las palabras clave que contiene el titular irá perdiendo fuerza cuanto más largo sea. Tanto en esta etiqueta como en otras (por ejemplo, la metaetiqueta title), Google confiere una mayor importancia a las primeras palabras de la frase que a las últimas: asegurate de que tu H1 empieza siempre que sea posible por la palabra o palabras claves principales para ese documento. Puede que esto vaya en contra de un titular de un estilo más periodístico, pero es lo ideal para posicionar el documento. Piensa en el contenido de la etiqueta como una frase que contenga información completa por si misma para definir el contenido del sitio, y que no necesite de información adicional.Además, de nada servirá el titular H1 si su título no hace realmente referencia al contenido de esa página. Las palabras clave del titular deben aparecer en varias ocasiones a lo largo del texto de contenido de la página.

  6.	El titular H1 puede o no coincidir con la metaetiqueta title del documento HTML. La metaetiqueta Title tiene una importancia menor que el H1, y se muestra en los resultados de búsqueda, por lo que podemos optimizar más para SEO el H1, y redactar la metaetiqueta title de tal forma que esté más destinada a captar la atención de un humano”

- Luego un encabezado con <h2> que diga:
“Etiqueta h2”

- Seguido de un texto con la etiqueta <p> que diga:
“La etiqueta H2 es un elemento similar al H1, que indica títulos de importancia para sub secciones del documento web actual. Por su naturaleza, puede haber varios H2 en un sitio, que indiquen los diferentes títulos de importancia de la pagina en la que nos encontramos. No debemos confundir los H2 con herramientas para colocar títulos en las zonas de nuestra página: "Últimas noticias", "Contactame",   "Zona de usuario", "Páginas amigas", "Bienvenido a mi web"… son títulos genéricos para bloques de una  web, pero que nada tienen que aportar al contenido. Además, de utilizar así los titulares H2 es muy   probable que fueran los mismos de una página a otra del sitio, y al igual que ocurría con los H1 es vital que sean diferentes, adaptados al contenido de cada documento. Los titulares H2 marcan las  diferentes secciones de un texto, los títulos de los nodos accesibles desde un listado de elementos,   etcétera. Su texto debe cumplir las mismas directrices que las dadas para el H1, pero sus palabras clave deben hacer referencia al texto que encontramos justo a continuación, o en la página a la que enlazan.  No existe un número determinado de elementos H2 que pueden colocarse en una página, pero el contenido  debe ser el que marque este requerimiento. Entre 2 y 8 titulares H2 son lo más adecuado, aunque pueden no aparecer o presentarse en un número mayor si la longitud del texto lo requiere.”

- Luego un encabezado con <h3> que diga:
“Etiqueta h3”

- Seguido de un texto con la etiqueta <p> que diga:
“Las etiquetas H3 en adelante nos permiten definir títulos de subapartados de un bloque encabezado con un H2. Su incidencia en SEO es más limitada, y por ello no es habitual ni recomendable el trabajar los  titulares a partir de H4. El orden lógico de los titulares debería ser el que apareciera en primer lugar  el titular H1, después todos los H2 y después todos los H3. También es habitual el trabajar con H1, H2 y  H3 como títulos de capítulo, apartados y epígrafes, de forma que aparezca primero el titular H1, después  un H2 con sus sub apartados marcados con H3, después otro H2 y sus sub apartados, y así sucesivamente.

- Realizar lo siguiente:
  - un encabezado con <h4> que diga: “Etiqueta h4”
  - un encabezado con <h5> que diga: “Etiqueta h5”
  - un encabezado con <h6> que diga: “Etiqueta h6”

- Luego se debe generar un texto que diga lo siguiente

<em> Etiqueta a </em>

- Seguido de un texto con la etiqueta <p> que diga:

>La etiqueta "a" es uno de los elementos más importantes del lenguaje HTML, esta etiqueta sirve para convertir texto normal en hipertexto, es decir, sirve para crear enlaces >(links). Con la etiqueta "a" pueden realizarse enlaces hacia documentos externos de cualquier tipo, generalmente es usada para definir enlaces hacia otras páginas web pero su uso >es más amplio y no necesariamente se tiene que realizar un enlace hacia un documento externo, pues la etiqueta: a permite realizar enlaces internos dentro de un mismo documento, >es decir, enlazar un texto hacia una parte especifica del mismo documento que lo incluye y de este modo poder navegar dentro del documento.

Pueden hacerlo de la manera en que se encuentra en el ejemplo o de como más les guste pero en cualquiera de los casos se debe comentar que hace cada etiqueta

Finalmente, dentro del body realizar los siguientes hipervínculos:
[http://bit.ly/2Tpkx2q](http://bit.ly/2Tpkx2q)
[http://bit.ly/2Z1oziB](http://bit.ly/2Z1oziB)

**EJERCICIO 5:**
	
- Generar el footer el cual debe tener el siguiente texto:

UTN <sub>(Universidad Tecnológica Nacional)</sub>


