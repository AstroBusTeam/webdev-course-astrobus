# Script — Lección 2: Introducción a HTML (8 min 2 seg)

## Objetivo de la lección
Reconocer etiquetas, elementos y atributos, y escribir la estructura básica de una página HTML.

## Progreso en la página
Al terminar esta lección, la página tiene la estructura básica completa (`doctype`, `html`, `head` y `body`), un título `h1` y un párrafo `p`.

## Recursos de la lección
- **Editor en línea:** CodePen
- **Código para practicar:** `/starter-files/lesson-2`
- **Código resuelto:** `/completed-examples/lesson-2`

---

## Guion

**[0:00 – 0:27 | Pantalla: Título de la lección]**

¡Hola de nuevo! Qué bueno que sigas aquí. En la lección anterior descubriste que una página web se construye con HTML y CSS. Hoy vas a dar un paso muy emocionante: vas a escribir tu primera página web con HTML, desde cero. Y te prometo algo: en los próximos diez minutos, tendrás una página funcionando en tu navegador.

Prepárate, abre tu mente y vamos con todo.

**[0:27 – 1:14 | Pantalla: Texto en pantalla: `<h1>Hola</h1>` con partes resaltadas]**

El HTML se escribe con etiquetas. Una etiqueta es una palabra clave escrita entre dos signos: el signo menor que, y el signo mayor que. Mira este ejemplo en pantalla. Tenemos una etiqueta que dice h1. Esa es la etiqueta de apertura, y le avisa al navegador que aquí empieza un título importante.

Después viene el contenido, que en este caso es la palabra Hola. Y al final, viene la etiqueta de cierre. Es igual a la de apertura, pero con una barra inclinada antes del nombre. Esa barra le avisa al navegador que el título ya terminó.

Casi todas las etiquetas del HTML funcionan en pareja: una que abre y otra que cierra. Es como abrir y cerrar un paréntesis al escribir.

```html
<h1>Hola</h1>
```

**[1:14 – 2:00 | Pantalla: Esquema: etiqueta de apertura + contenido + etiqueta de cierre = elemento]**

Hay una forma muy fácil de recordar esto. Imagina una caja de cartón. La etiqueta de apertura es la que abre la caja. Dentro de la caja va el contenido, como esta estrella. Y la etiqueta de cierre es la que cierra la tapa de la caja.

Cuando juntas las tres partes, la de apertura, el contenido y la de cierre, obtienes lo que se llama un elemento. Entonces, un elemento HTML es una caja completa, con su inicio, su contenido y su final. Por ejemplo, el elemento p sirve para escribir un párrafo, y se escribe con la etiqueta p al comienzo, el texto en medio, y la etiqueta p con barra al final.

Recuerda: elemento es igual a apertura, más contenido, más cierre.

```html
<p>Un párrafo de texto</p>
```

**[2:00 – 3:40 | Pantalla: Abrir el editor con el código inicial, Pantalla: Resaltar `<!DOCTYPE html>`, Pantalla: Resaltar `<html lang="es">`]**

Pasemos a la práctica. Estamos en CodePen, y aquí tengo la estructura básica de toda página HTML. CodePen ya la prepara por detrás, pero conviene que la conozcas, porque la necesitarás en cualquier página real. Fíjate bien, porque estas líneas aparecen en casi todas las páginas del mundo.

Vamos a revisarlas una por una, con calma, para que entiendas qué significa cada parte y para qué sirve.

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Título de la página</title>
</head>
<body>
  <!-- Escribe aquí tu código -->
</body>
</html>
```

La primera línea dice doctype html. Esta línea no se ve en la página, pero es muy importante. Le avisa al navegador que vamos a usar HTML moderno, para que interprete todo correctamente. Piensa que es como el saludo al llegar a un lugar nuevo: presenta tu página al navegador.

Siempre debe ir al principio, y no necesitas memorizarla, porque se escribe igual en todas las páginas.

```html
<!DOCTYPE html>
```


La siguiente etiqueta es html. Es la que envuelve absolutamente todo el contenido de la página, como una gran caja que guarda todas las demás cajas. Ahora fíjate en esta parte: lang igual a es, entre comillas. Esto se llama un atributo. Un atributo es un dato extra que le agregas a una etiqueta para darle más información.

Es como una etiqueta colgante en una maleta, que cuenta algo más sobre ella. En este caso, el atributo lang le dice al navegador que la página está escrita en español, porque es significa español. Un atributo siempre se escribe con un nombre, un signo igual, y un valor entre comillas.

Esa forma se repite siempre, así que ya la puedes reconocer. Más adelante conocerás otros atributos.

```html
<html lang="es">
  ...
</html>
```

**[3:40 – 4:30 | Pantalla: Resaltar `<head>` y `<title>`]**

Dentro de html encontramos dos grandes secciones. La primera es head, que significa cabeza. Aquí se guarda información sobre la página que no se ve directamente en la pantalla. Por ejemplo, dentro del head está el elemento title, que es el nombre de la página.

Ese texto aparece en la pestaña del navegador, arriba, donde ves los nombres de las páginas abiertas. Voy a escribir aquí el nombre de mi página: Mi primera página. En CodePen no lo verás reflejado en la pantalla, pero en una página real ese nombre aparecería en la pestaña.

También hay una línea llamada meta charset, que permite que se muestren bien las tildes y la letra eñe. Déjala siempre ahí, porque sin ella las tildes podrían verse como símbolos extraños. Recuerda: el head guarda información de la página, y el body guarda lo que se ve.

```html
<head>
  <meta charset="UTF-8">
  <title>Mi primera página</title>
</head>
```

**[4:30 – 5:50 | Pantalla: Resaltar `<body>`,`<h1>¡Hola, mundo!</h1>`]**

La segunda gran sección se llama body, que significa cuerpo. Aquí va todo lo que sí se ve en la página: los títulos, los párrafos, las imágenes y mucho más. Esta es tu zona de trabajo. Todo lo que escribas dentro del body aparecerá en la pantalla.

Fíjate que también tiene su etiqueta de apertura y su etiqueta de cierre. Y por ahora, el cuerpo de nuestra página está vacío, como una hoja en blanco lista para que empieces a escribir. Si la página fuera una casa, el body sería la parte que sí puedes ver y recorrer.

```html
<body>
  <!-- Aquí va lo que se ve en la página -->
</body>
```

Llegó el momento de escribir nuestro primer contenido. Dentro del body, voy a escribir un título. Abro la etiqueta h1, que significa encabezado de nivel uno, el más importante de todos. Dentro escribo: ¡Hola, mundo! Y ahora cierro la etiqueta, con la barra inclinada. ¡Mira lo que apareció en la pantalla!

Un título grande, en negrita. Ya tienes algo visible. Ese es el poder del HTML: escribes una etiqueta, y el navegador la transforma en algo que puedes ver. Y esto es solo el comienzo. Y fíjate en un detalle importante: cerré la etiqueta apenas terminé de escribir el contenido.

El h1 se usa una sola vez por página, para el título principal, como el nombre en la portada de un libro.

```html
<h1>¡Hola, mundo!</h1>
```

**[5:50 – 6:25 | Pantalla: Escribir `<p>Esta es mi primera página web.</p>`]**

Ahora vamos a agregar un párrafo, que es un texto normal. Debajo del título, abro la etiqueta p. Dentro escribo: Esta es mi primera página web. Y cierro la etiqueta p, con su barra. ¡Listo! Ahí aparece el texto, justo debajo del título. Mira cómo el navegador los separó automáticamente.

Ya tienes una página con un título y un párrafo. Y todo lo hiciste con tan solo dos elementos HTML. Puedes escribir todos los párrafos que quieras: cada uno lleva su propia etiqueta p de apertura y de cierre.

```html
<p>Esta es mi primera página web.</p>
```

**[6:25 – 6:49 | Pantalla: Mostrar un error común: etiqueta sin cerrar]**

Te voy a contar el error más común de los principiantes. Es olvidarse de cerrar una etiqueta. Mira esta caja: tiene la tapa abierta y el contenido se cae por todos lados. Eso mismo pasa cuando una etiqueta no se cierra: el navegador se confunde y la página se ve rara.

Por eso, cada vez que abras una etiqueta, ciérrala enseguida, y escribe el contenido en medio.


**[6:49 – 7:36 | Pantalla: Pausa para practicar]**

Ahora es tu turno de crear tu propia página. Abre el enlace que está en la descripción de este video. Vas a encontrar la estructura básica lista. Dentro del body, escribe un título con la etiqueta h1 que diga tu nombre. Después, debajo, escribe un párrafo con la etiqueta p, contando algo sobre ti, por ejemplo cuántos años tienes o qué te gusta hacer.

No olvides cambiar también el título de la pestaña, el elemento title. Y recuerda: cada etiqueta que abres, debes cerrarla. Tómate tu tiempo, y no te preocupes si te equivocas, porque equivocarse es parte de aprender. Si algo no aparece en la pantalla, revisa que hayas escrito la etiqueta de apertura y la de cierre, con la barra inclinada.

Pausa el video y practica ahora.


**[7:36 – 8:01 | Pantalla: Resumen: etiqueta, elemento, atributo, estructura]**

¡Excelente trabajo! Hoy aprendiste mucho. Viste qué es una etiqueta, qué es un elemento, y qué es un atributo. Conociste la estructura básica de una página, con doctype, html, head y body. Y creaste tu primera página con un título y un párrafo. En la próxima lección vamos a hacerla mucho más completa, con listas, imágenes y enlaces.

¡Te espero ahí!

---

## Puntos clave para mostrar en pantalla (anotaciones)
- Etiqueta de apertura `<p>` y etiqueta de cierre `</p>`
- Elemento = apertura + contenido + cierre
- Atributo → `nombre="valor"`, por ejemplo `lang="es"`
- La estructura: `doctype`, `html`, `head` y `body`
- `h1` → título principal; `p` → párrafo
