# Script — Lección 3: Añadir más elementos HTML (8 min)

## Objetivo de la lección
Usar encabezados, listas, imágenes y enlaces para completar una página.

## Progreso en la página
Al terminar esta lección, la página incorpora un subtítulo, una lista de tres elementos, una imagen con texto alternativo y un enlace.

## Recursos de la lección
- **Editor en línea:** CodePen
- **Código para practicar:** `/starter-files/lesson-3`
- **Código resuelto:** `/completed-examples/lesson-3`

---

## Guion

**[0:00 – 0:30 | Pantalla: Título y la página de la lección 2]**

¡Bienvenido de nuevo! En la lección anterior creaste tu primera página, con un título y un párrafo. Hoy vamos a hacerla mucho más completa. Aprenderás a organizar tu contenido con encabezados, a escribir listas, a mostrar imágenes y a crear enlaces para ir a otras páginas.

Seguimos en CodePen, y partimos de la página que ya tenías. ¡Manos a la obra!

**[0:30 – 1:30 | Pantalla: Mostrar `h1` a `h6` con tamaños distintos]**

Empecemos por los encabezados. Ya conoces el h1, que es el título más importante. Pero en realidad existen seis niveles de encabezado, que van de h1 hasta h6. Mira la escalera en pantalla: el h1 es el más grande y el más importante, y a medida que el número sube, el encabezado se hace más pequeño y menos importante.

Piensa en los títulos de un cuaderno: el nombre de la materia es el título grande, y cada tema es un subtítulo más pequeño. En una página web pasa igual. Usa un h1 para el título principal, y h2 para las secciones de tu página.

Los niveles h4, h5 y h6 los usarás muy poco, así que por ahora concéntrate en h1 y h2.

**[1:30 – 2:00 | Pantalla: Escribir el `h2` en el editor]**

Vamos a practicarlo. Debajo del párrafo que ya teníamos, voy a escribir un subtítulo. Abro la etiqueta h2, escribo: Mis cosas favoritas, y cierro la etiqueta h2. ¡Mira! Apareció un título más pequeño que el principal. Con él vamos a abrir una nueva sección en nuestra página, donde contaremos qué nos gusta.

Fíjate que el h2 se ve más pequeño que el h1, justo como en la escalera.

```html
<h2>Mis cosas favoritas</h2>
```

**[2:00 – 2:30 | Pantalla: Esquema de lista con viñetas]**

Ahora vamos con las listas. Una lista con viñetas sirve para enumerar cosas sin un orden especial, igual que tu lista de cosas para un paseo. Usamos dos etiquetas que trabajan juntas. La primera es ul, que significa lista sin orden en inglés, y envuelve toda la lista.

La segunda es li, que significa elemento de lista, y se usa una vez por cada punto.

**[2:30 – 3:30 | Pantalla: Escribir la lista con tres elementos]**

Escribamos una. Debajo del subtítulo, abro la etiqueta ul. Dentro, abro la etiqueta li y escribo: Videojuegos. Cierro la li. Hago lo mismo con la segunda: abro li, escribo Música, y cierro li. Y una tercera: Deportes. Para terminar, cierro la etiqueta ul, que es la que envolvía toda la lista.

¡Mira! Tenemos una lista con tres puntos, cada uno con su viñeta. Fíjate que cada li está dentro del ul, como cajitas guardadas dentro de una caja más grande. Y recuerda: puedes cambiar los textos por lo que a ti te guste. Si quisieras una lista con números, en lugar de viñetas, usarías la etiqueta ol en lugar de ul.

Los elementos li se escriben exactamente igual. Pruébala cuando termines la práctica, si te animas, y observa la diferencia. Es un buen reto.

```html
<ul>
  <li>Videojuegos</li>
  <li>Música</li>
  <li>Deportes</li>
</ul>
```

**[3:30 – 4:15 | Pantalla: Resaltar `src` y `alt` en la etiqueta `img`]**

Es hora de las imágenes. Para mostrarlas se usa la etiqueta img. Esta etiqueta es especial, porque no necesita etiqueta de cierre: no tiene contenido en medio, solo atributos. Y usa dos atributos muy importantes, que debes aprender bien: uno dice dónde está la imagen y otro la describe.

El primero es src, que significa fuente, y sirve para decir dónde está la imagen, con la dirección de internet. El segundo es alt, que significa texto alternativo, y sirve para describir la imagen con palabras, por ejemplo: Una montaña con un sol.

**[4:15 – 5:15 | Pantalla: Escribir la etiqueta `img`]**

Vamos a agregar una. Debajo de la lista, escribo la etiqueta img. Después, el atributo src, el signo igual, y entre comillas la dirección de una imagen de ejemplo. Luego, el atributo alt, y entre comillas: Imagen de ejemplo. Y cierro con el signo mayor que.

¡Ahí aparece la imagen! Ahora, una pregunta importante: ¿para qué sirve el texto alt? Sirve para que las personas con discapacidad visual, que usan programas que leen la pantalla en voz alta, sepan qué hay en la imagen. Y también aparece si la imagen no carga.

Por eso, escribe siempre el texto alt. Es una buena práctica de todo programador, y hace que tu página sea amable con todas las personas. Ya ves que no es tan difícil: dos atributos, y la imagen está lista.

```html
<img src="https://placehold.co/300x200" alt="Imagen de ejemplo">
```

**[5:15 – 6:00 | Pantalla: Resaltar `href` en la etiqueta `a`]**

Ahora aprenderemos a crear un enlace, esa palabra o texto sobre el que haces clic para viajar a otra página. Se hace con la etiqueta a, que viene de la palabra ancla. Esta etiqueta lleva un atributo llamado href, que sirve para decir a dónde va el enlace, con la dirección de la otra página.

Y el texto que escribes entre la etiqueta de apertura y la de cierre es lo que la persona ve y toca. Por ejemplo, si quieres un enlace que diga Aprende más, ese texto va en medio.

**[6:00 – 6:30 | Pantalla: Escribir el enlace y probarlo]**

Escribámoslo. Dentro de un párrafo que dice Aprende más en, abro la etiqueta a, escribo el atributo href, el signo igual, y entre comillas la dirección completa, que empieza con https. Agrego también target igual a blank, para que el enlace se abra en una pestaña nueva.

Cierro con el signo mayor que, y escribo el texto: MDN Web Docs. Cierro la etiqueta a. Ahora lo probamos: hago clic en el enlace... ¡y funciona! Nos lleva directo a otra página, justo como queríamos.

```html
<p>Aprende más en <a href="https://developer.mozilla.org/es/" target="_blank">MDN Web Docs</a>.</p>
```

**[6:30 – 7:30 | Pantalla: Pausa para practicar]**

Ahora te toca practicar. Abre el enlace que está en la descripción del video. Vas a agregar cuatro cosas a tu página. Primero, un subtítulo con la etiqueta h2. Segundo, una lista de tres cosas que te gustan, con las etiquetas ul y li. Tercero, una imagen con la etiqueta img, sin olvidar su atributo alt.

Y cuarto, un enlace con la etiqueta a y el atributo href. Si algo no funciona, revisa que cada etiqueta que abriste esté bien cerrada, y que las comillas de los atributos estén completas. Y si te sobra tiempo, intenta el reto extra: crear una página con tu receta favorita, con una lista de ingredientes y otra de pasos.

Pausa el video y practica ahora.

**[7:30 – 8:00 | Pantalla: Resumen con las 4 etiquetas: `ul`/`li`, `img`, `a`, `h2`]**

¡Muy bien! Hoy aprendiste cuatro herramientas nuevas. Los subtítulos con h2, las listas con ul y li, las imágenes con img, y los enlaces con la etiqueta a. Tu página ya tiene mucho más contenido, pero todavía se ve muy simple, con letras negras sobre un fondo blanco.

En la próxima lección vamos a darle color y estilo con CSS. ¡Te espero!

---

## Puntos clave para mostrar en pantalla (anotaciones)
- `h1` a `h6` → niveles de encabezado
- `ul` + `li` → lista con viñetas
- `img` → `src` (dónde está) y `alt` (qué muestra)
- `a` + `href` → enlace
- Cada etiqueta que se abre, se cierra
