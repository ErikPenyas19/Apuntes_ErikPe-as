# Apuntes_ErikPenyas

# Markdown

## Encabezado 1
### Encabezado 2
#### Encabezado 3
##### Encabezado 4

Para escribir un texto en cursiva pondremos (*) o (_) delante y atrás del texto que deseemos.
*Este texto está escrito en cursiva*
_Este texto está escrito en cursiva_

Para escribir un texto en cursiva pondremos (**) o (__) delante y atrás del texto que deseemos.
**Este texto está escrito en negrita**
__Este texto está escrito en negrita__

Se pueden combinar las formas de texto si mezclamos los modos de manera ordenada, es decir, delante (_**) y detrás (**_) o cambiando los símbolos.
__**Este texto está escrito en negrita y en cursiva a la vez**__

Mi nombre es **__Erik__** y estoy en el aula 301.

Lista ordenada:
  1. Uno
  2. Dos
  3. Tres

Para hacer una lista desordenada, basta con poner un guión (-) o un punto (·) en cada elemento de la lista.

Lista desordenada:
- Uno
- Dos
- Tres

```
 <html>
  <head>
  </head>
 </html>
```
```
  [Enlace wikipedia](https://es.wikipedia.org/wiki/Wikipedia:Portada "Click aquí") Para colocar un enlace
```
 
 [Enlace wikipedia](https://es.wikipedia.org/wiki/Wikipedia:Portada "Click aquí")

```
  ![Foto](https://github.com/ErikPenyas19/TestMarkDown/blob/main/rECORTE%20RANDOM.PNG "XD") Para colocar una imagen
```

![Foto](https://github.com/ErikPenyas19/TestMarkDown/blob/main/rECORTE%20RANDOM.PNG "XD")



Para hecer una tabla lo único que hay que saber es que para separar columnas hay que utilizar (|) y que para ajustar el texto podemos usar:

- | ---- | : Para ajustar a la izquierda
- | :--- | : Para ajustar al medio
- | ---: | : Para ajustar a la derecha

| Encabezado1 | Encabezado2 | Encabezado3 |
| ----------- |:-----------:| -----------:|
| Item1 | Bolígrafos | 20€ |
| Item2 | Grapadoras | 100€ |
| Item3 | Lápices | 60€ |


# HTML

## Etiquetas

Todas las etiquetas se abren con <nombreetiqueta> y se cierran con </nombreetiqueta> después de unos parágrafos.

Hay distintas etiquetas para formar una página web

| Etiqueta | Función | Cómo marcar la etiqueta |
| -------- | ------- | ----------------------- |
| **head** | definición/información principal del documento | "< head > < /head >"
| **body** | Escribir dentro de la etiqueta significa que lo que escribas como texto se verá en la página | "< body > < /body >"
| **etiqueta de comentario** | inserta comentario que no aparece en la página | "< !--comentario-- >"
| **p** | Crear párrafo en el ''body'' para poner texto | "< p > < /p >"
| **br** | Salto de línea más grande porque también incluye bordes | "< br >"
| **br /**| Salto de línea forzado en medio de una frase, para seguirla más abajo | "< br / >"
| **div** | Estructurar documentos | "< div >"
| **table** |
| **a** | Poner un enlace. El enlace hay que colocarlo en href='' | "< a href='' > < /a >"
| **ol**| Crear una lista ordenada y/o desordenada | "< ol > < /ol >"
| **li** | Hacer punto de la lista ordenada | "< li > < /li >"
| **ul** | Hacer punto de la lista desordenada | "< ul > < /ul >"
| **strong** | Modifica el texto de dentro para que sea en **negrita** | "< strong > < /strong >"
| *em* | Modifica el texto de dentro para que sea en _cursiva_ | "< em > < /em >"

Sangrado:

importante que la primera página se llame /indexhtml
lang='es' : Lenguaje en español

meta charset='UTF-8': Configuración para mostrar carácteres de un lenguaje, es decir, UTF-8 sirve para carácteres de español como la 'ñ'

##Atributs Core

- **id**: Identifica el elemento. No puede haber dos elementos en un mismo documento con el mismo id.
- **class**: Sirve para asociar un elemento a una clase. Más de un elemento puede estar en una misma clase.
- **styles**: Se usa para definir el estilo del elemento.
- **title**: Se usa para poner un texto con una breve información del elemento. Muchos navegadores muestran este texto cuando se pasa por encima del elemento.

#CSS

Para crear un archivo CSS es importante crearlo con un nombre que sea **styles.css** o **estilos.css**. Este archivo funciona como un elemento _style_, en el que podremos modificar la forma en la que se verá nuestra página web.

Para poder modificar cómo deseamos debemos tener en cuenta la siguiente tabla:

| **Selector** | **Ejemplo** | **Explicación** |
| ------------ | ----------- | --------------- |
| *#id* | #intro | Selecciona los elementos con id _intro_ |
| *.class* | .intro | Selecciona los elementos con clase _intro_ |
| *elemento.class* | p.intro | Selecciona los elementos _p_ con clase _intro_ |
| *elemento* | p | Selecciona los elementos _p_ |
| *elemento, elemento,...* | div, p | Selecciona todos los elementos que sean _div_ y _p_ |
| *** | * | Selecciona **TODOS** los elementos |
| *elemento<elemento2* | p<div | Selecciona los elementos _p_ que son hijos directos de un _div_ |

##Atributos 

- _**margin**_: 
- _**padding**_: 
- _**text-align**_: 
- _**text-justify**_: 
- _**border-radius**_: 
- _**text-decoration**_: 
- _**size**_: Ajustar el tamaño del texto
- _**width**_: Ajustar la anchura de una foto
- _**height**_: Ajustar la altura de una foto
- _**background-color**_: 
- _**font-family**_: 
