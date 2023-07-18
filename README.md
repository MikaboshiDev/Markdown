# Guia de Uso de Markdown

A continuación se presentan los comandos más utilizados en Markdown apartir de una guia de node school que anteriormente se realizó en el curso de [Node.js](
sin mas por el momento empezemos.

## 🤭 Titulos Ejercicio 2.

Si necesitas agregar un encabezado simple agrege # al comienzo de l linea. El nummero de # indica el nivel del encabezado.

# Encabezado 1

## Encabezado 2

### Encabezado 3

#### Encabezado 4

##### Encabezado 5

###### Encabezado 6

como en html hay 6 niveles de encabezados en estos titulos seran transformados a etiquetas h1 - h6 en consecuencia.
Hay alias para los encabezados de primer y segundo nivel, obtendras de primer nivel si escribes tres signos === en la siguiente linea, tambien puedes escribir tres ---
para obtener un encabezado de segundo nivel.

# Encabezado 1

## Encabezado 2

## 🧑‍⚕️ Enfasis Ejercicio 3.

Es facil marcar el texto como **cursiva, negrita, combinado o tachado**. Hay algunas formas de hacer enfasis en Markdown y cada una de ellas es legible.
Para enfatisar simplemente envuelva un texto en comillas simples o dobles y/o triples.

| Tipo de Enfasis | Sintaxis                  | Ejemplo         |
| --------------- | ------------------------- | --------------- |
| Cursiva         | `*texto*` o `_texto_`     | _cursiva_       |
| Negrita         | `**texto**` o `__texto__` | **negrita**     |
| Combinado       | `**_texto_**`             | **_combinado_** |
| Tachado         | `~~texto~~`               | ~~tachado~~     |

## 📝 Listas Ejercicio 4.

Las listas son importantes para la informacion estructurada. No hay nada dificil en la creacion de listas en Markdown simplemente incerte un arterisco (\*) o un guion (-) antes de cada
elemento para una lista desordenada o un numero con un punto para una lista ordenada.

### Lista Desordenada

-  Articulo Num 1
-  Item 2
-  Item 3
-  Item 4
-  Item 5

### Listas Ordenadas

1. Articulo 1
2. Item 2
3. Item 3
4. Item 4
5. Item 5

### Listas Anidadas

No hay nada dificl en hacer listas anidadas simplemente agrege una pestaña o espacio para elementos anidados. Para las listas con asteriscos (\*) o con guiones (-) tambien funciona

-  Elemento 1
   -  Elemento 1.1
-  Elemento 2
   -  Elemento 2.1

## 👍 Enlaces Ejercicio 5.

A menudo necesitamos hacer referencia para algo. Hay dos formas de crear enlaces en markdown uno es por medio de estilo de linea y otro es referenciado. Por cierto la forma mas facil es simplemente
pegar el enlace esn un archivo de markdown.

Ejemplo:
https://www.google.com o <https://www.google.com>

### Estilo de Linea.

Los enlaces de markdown tienen este formato `[texto](href "alt")`.
Arriba texto es texto que sera del enlace, href es una referencia similar a los atributos href de HTML, alt es un texto alternativo para enlace igual similar a los atributos html. El texto de un enlace
puede tener cualquier formato, lo que significa que se puede usar de enfasis si es que es necesario.

Ejemplo:
`    [Google](https://www.google.com)
    [Pagina principal de google](https://www.google.com "Pagina principal de google")
   `

-  [Google](https://www.google.com)
-  [Pagina principal de google](https://www.google.com 'Pagina principal de google')

### Estilo de Referencia.

A veces tienes que usar el mismo enlace en diferentes lugares por lo que sera conveniente utilizar una referencia para todos los enlaces. Entonces puedes hacer algo asi:

[Sitio de NodeSchool][ref]
[Github][1]
[Analisis de Comentarios]

Algunos texto para mostrar que los enlaces de referencia pueden seguir mas adelante.

[ref]: https://www.google.com
[1]: https://www.github.com
[Analisis de Comentarios]: https://remark.js.org/

Como puede notar arriba las referencias no distiguen entre mayusculas o minusculas y usted es libre de usar numeros como referencia o usar el texto del enlace como el mismo.
