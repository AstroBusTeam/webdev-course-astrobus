# Script — Lección 5: Crear una página web sencilla (12 min 21 seg)

## Objetivo de la lección
Combinar HTML y CSS para construir una página de perfil personal, de forma ordenada y paso a paso.

## Progreso en la página
Al terminar esta lección, el estudiante tiene su propia página de perfil dentro de una tarjeta centrada, lista para compartir.

## Recursos de la lección
- **Editor en línea:** CodePen
- **Código para practicar:** `/starter-files/lesson-5`
- **Código resuelto:** `/completed-examples/lesson-5`

---

## Guion

**[0:00 – 0:46 | Pantalla: Título y la página de perfil terminada]**

¡Hola! Llegó el momento más emocionante del curso. Mira esta página que tengo aquí. Es una página de perfil personal: tiene un nombre, una foto, un texto que cuenta algo sobre la persona, una lista de pasatiempos y un enlace. Está dentro de una tarjeta con un borde de color, y se ve muy bien.

Pues, ¿sabes qué? En esta lección vamos a construirla juntos, paso a paso, usando todo lo que aprendiste en las lecciones anteriores: etiquetas, listas, imágenes, enlaces y estilos con CSS. Al final, vas a tener tu propia página, con tu nombre y tus gustos, que podrás compartir con tu familia y tus amigos.

No necesitas saber nada más que lo que ya viste en este curso. ¿Estás listo? ¡Empecemos!

**[0:47 – 1:31 | Pantalla: Boceto en papel o en pantalla de la página: nombre, foto, descripción, lista, enlace]**

Antes de escribir una sola línea de código, los programadores siempre hacen algo muy importante: planifican. Y lo más fácil es hacer un boceto, es decir, un dibujo sencillo, con lápiz y papel. Mira el mío. Arriba, voy a poner mi nombre, como título. Debajo, una foto en un círculo.

Luego, un párrafo corto contando algo sobre mí. Después, una lista con mis pasatiempos. Y al final, un enlace a mi sitio favorito. Con este dibujo ya sé exactamente qué etiquetas necesito: un título, una imagen, un párrafo, una lista y un enlace. Planificar te ahorra tiempo y evita que te pierdas a la mitad del camino.

Te recomiendo que hagas tu propio boceto antes de seguir.

**[1:32 – 2:16 | Pantalla: Abrir el proyecto inicial en el editor en línea]**

Ahora abramos nuestro proyecto en CodePen, el mismo editor que venimos usando. Tenemos tres paneles: el de HTML, el de CSS y el de JS. Hoy solo usaremos los dos primeros, porque el de JS es para JavaScript, que verás más adelante. En el panel de HTML va el contenido, y en el de CSS va el estilo.

Recuerda que CodePen ya prepara por detrás la estructura de la página, con doctype, html, head y body, así que aquí solo escribimos lo que va dentro del body. En el panel de HTML hay unos comentarios que me recuerdan los pasos que debo seguir.

Los comentarios son notas que escribimos para nosotros mismos, y no se ven en la página. ¡Vamos a seguirlos!

**[2:17 – 2:44 | Pantalla: Escribir el `h1`]**

Paso uno: el nombre. Dentro del body, abro una etiqueta h1 y escribo un título de bienvenida, por ejemplo: Hola, soy Alex. Aquí tú escribirás tu propio nombre. Cierro la etiqueta h1. ¡Listo! Ya tenemos el título principal de nuestra página. Fíjate que lo escribí con una sola etiqueta h1, igual que aprendimos en la segunda lección.

Tú decides cómo se presenta tu página al mundo.

```html
<h1>Hola, soy Alex</h1>
```

**[2:45 – 3:30 | Pantalla: Agregar la imagen con `alt`]**

Paso dos: la foto. Debajo del título, escribo la etiqueta img, con el atributo src, y entre comillas la dirección de una imagen. Para esta práctica usaremos una imagen de ejemplo, y tú puedes usar otra que te guste, siempre que sea una dirección de internet.

Después escribo el atributo alt, con el texto: Foto de perfil. Recuerda que el texto alt describe la imagen con palabras, y que es una muy buena costumbre escribirlo siempre. Cierro con el signo mayor que. ¡Y ahí aparece la imagen! Si quieres usar una foto tuya o un dibujo que hiciste, primero tendrías que subirlo a internet, y después copiar su dirección.

Para esta práctica, usa una imagen de ejemplo.

```html
<img src="https://placehold.co/200x200" alt="Foto de perfil">
```

**[3:31 – 4:20 | Pantalla: Agregar párrafo, `h2` y lista]**

Pasos tres y cuatro. Ahora escribo un párrafo con la etiqueta p, contando algo sobre mí: Tengo catorce años y me encanta crear cosas nuevas. Después, un subtítulo con la etiqueta h2, que diga: Mis pasatiempos. Y debajo, una lista con las etiquetas ul y li.

Mis tres pasatiempos serán: Dibujar, Jugar fútbol y Escuchar música. Cada uno va dentro de su propia etiqueta li, y todos dentro del ul. Puedes cambiar estos textos por los tuyos, claro que sí. ¡Mira cómo va quedando nuestra página! Observa que, para escribir la lista, primero abrí la etiqueta ul, después escribí los tres elementos li, uno por uno, y al final cerré el ul.

Ese orden es muy importante.

```html
<p>Tengo 14 años y me encanta crear cosas nuevas.</p>

<h2>Mis pasatiempos</h2>
<ul>
  <li>Dibujar</li>
  <li>Jugar fútbol</li>
  <li>Escuchar música</li>
</ul>
```

**[4:21 – 4:58 | Pantalla: Agregar el enlace]**

Y el último paso del contenido: el enlace a mi sitio favorito. Escribo un párrafo con el texto: Mi sitio favorito, dos puntos. Y dentro del párrafo, abro la etiqueta a, con el atributo href, y entre comillas, la dirección de una página web. Escribo el texto del enlace: MDN Web Docs.

Cierro la etiqueta a, y cierro el párrafo. Probemos el enlace con un clic: ¡funciona! Y con esto, terminamos todo el contenido de nuestra página. Ya tenemos un título, una imagen, un párrafo, una lista y un enlace. Y todo con HTML. Fíjate que el enlace está dentro de un párrafo, y eso es perfectamente normal: los elementos se pueden guardar unos dentro de otros, como cajas dentro de cajas.

Cierra primero la etiqueta que abriste último.

```html
<p>Mi sitio favorito: <a href="https://developer.mozilla.org/es/" target="_blank">MDN Web Docs</a></p>
```

**[4:59 – 5:53 | Pantalla: Pausa para practicar 1]**

Es tu turno de construir el contenido de tu propio perfil. Abre el enlace de la descripción, donde encontrarás el proyecto inicial con los comentarios de los pasos. Sigue los cinco pasos con tu propia información. Primero, tu nombre en un título h1. Segundo, una imagen con su texto alt.

Tercero, un párrafo contando algo sobre ti. Cuarto, una lista con tus pasatiempos favoritos. Y quinto, un enlace a tu sitio preferido. Revisa que cada etiqueta que abres esté bien cerrada. Y prueba tu página después de cada paso, no solo al final, porque así detectas los errores más rápido.

Pausa el video y practica ahora. Aquí te espero.

**[5:54 – 6:17 | Pantalla: Mostrar la página sin estilo]**

Bienvenido de nuevo. Ya tenemos todo el contenido de la página, pero fíjate cómo se ve: todo está pegado a la izquierda, con letras negras sobre fondo blanco, y sin ningún adorno. Es hora de darle estilo con CSS. ¡Vamos a convertirla en una página muy bonita!

Y recuerda que no tenemos que tocar nada del contenido: todo el cambio se hace en el archivo de estilo.

**[6:18 – 7:05 | Pantalla: Escribir los estilos del `body`]**

Pasamos al panel de CSS. Empezamos por el body, que afecta a toda la página. Escribo el selector body, abro las llaves, y escribo tres propiedades. La primera, background-color, con un azul muy claro. La segunda, font-family, con Arial y sans-serif como opción de respaldo.

Y la tercera, padding, que significa relleno, con un valor de veinte píxeles. El padding crea un espacio interior entre el borde de la página y el contenido, para que nada quede pegado a los bordes. También escribo la propiedad margin con un valor de cero.

El margin es el espacio exterior, y lo dejamos en cero para quitar el margen que el navegador pone por defecto. Mira cómo cambió: ya tenemos un fondo de color y una letra más moderna.

```css
body {
  background-color: #e0f2fe;
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 20px;
}
```

**[7:06 – 7:58 | Pantalla: Envolver el contenido en `<div class="tarjeta">`]**

Ahora viene una idea nueva y muy útil. Queremos que todo el contenido esté dentro de una tarjeta, como una cajita blanca con borde. Para eso, necesitamos agrupar todos los elementos. Y lo hacemos con la etiqueta div, que es una caja sin ningún significado especial, solo sirve para agrupar cosas.

Voy al panel de HTML, y al comienzo de mi código escribo una etiqueta div. Y al final de todo, cierro esa etiqueta div. Así, todo el contenido queda guardado dentro de la caja. Pero necesitamos poder darle estilo a esa caja y no a otras.

Para eso usamos una clase. Una clase es un nombre que le pones a un elemento, con el atributo class. Le pongo a mi div el nombre tarjeta. Así queda: div class igual a tarjeta. Ahora puedo hablarle al CSS de esa caja en particular.

```html
<div class="tarjeta">
  <!-- todo el contenido de la página -->
</div>
```

**[7:59 – 9:21 | Pantalla: Escribir `.tarjeta { ... }`]**

Vamos al CSS. Para darle estilo a una clase, el selector se escribe con un punto, seguido del nombre de la clase. Escribo punto tarjeta, y abro las llaves. Ahora, las propiedades. Primero, background-color, con el valor white, que significa blanco, para que la tarjeta se destaque del fondo azul.

Segundo, max-width, que significa ancho máximo, con el valor de cuatrocientos píxeles. Esto evita que la tarjeta se estire demasiado en pantallas grandes. Tercero, padding con veinte píxeles, para dejar espacio interior. Cuarto, border, con tres píxeles, línea sólida, y un color azul. Quinto, border-radius, con doce píxeles, para redondear las esquinas.

Sexto, text-align con el valor center, para centrar el texto. Y por último, la propiedad que centra la tarjeta en la pantalla: margin, con el valor cero auto. Esto significa cero arriba y abajo, y automático a los lados, lo que reparte el espacio de manera igual a la izquierda y a la derecha.

¡Mira qué bonita quedó nuestra tarjeta, justo en el centro! Tómate un momento para observar todas las propiedades que usamos, porque las vas a necesitar muchas veces. Puedes cambiar los números y los colores para ver cómo se transforma la tarjeta.

```css
.tarjeta {
  background-color: white;
  max-width: 400px;
  margin: 0 auto;
  padding: 20px;
  border: 3px solid #0284c7;
  border-radius: 12px;
  text-align: center;
}
```

**[11:30 – 12:30 | Pantalla: Agregar estilos de `h1`, `img` y `a`]**

Solo nos faltan unos detalles. Primero, el título. Con el selector h1, cambio el color a un azul oscuro. Segundo, la imagen. Con el selector img, uso border-radius con el valor cincuenta por ciento. Esto redondea tanto la imagen que se convierte en un círculo perfecto, ideal para una foto de perfil.

Y tercero, el enlace. Con el selector a, le doy el color rojo. Por último, para la lista, uso list-style-position con el valor inside, para que las viñetas queden dentro de la tarjeta, y padding cero. ¡Y listo! Nuestra página de perfil está terminada, y se ve muy profesional.

Mira cómo cambió desde donde empezamos: es la misma información, pero con un estilo que la hace especial.

```css
h1 {
  color: #0369a1;
}

img {
  border-radius: 50%;
}

ul {
  list-style-position: inside;
  padding: 0;
}

a {
  color: #dc2626;
}
```

**[12:30 – 13:30 | Pantalla: Pausa para practicar 2]**

Ahora vas a darle estilo a tu perfil. Abre el panel de CSS. Primero, escribe la regla del body, con un color de fondo, una fuente y un poco de padding. Segundo, agrupa todo tu contenido dentro de un div con la clase tarjeta, y escribe la regla punto tarjeta, con fondo, borde, esquinas redondeadas, ancho máximo y margin cero auto para centrarla.

Tercero, dale color a tu título y haz tu foto redonda, con border-radius al cincuenta por ciento. Usa los colores que más te gusten, tú eres el diseñador. Si lo terminas pronto, intenta el reto extra: agrega una segunda tarjeta con el título Mis metas, reutilizando la misma clase.

Pausa el video y practica ahora. Tómate todo el tiempo que necesites.

**[13:30 – 14:15 | Pantalla: Probar y corregir un error a propósito]**

Antes de terminar, quiero que sepas qué hacer si algo no funciona, porque a todos nos pasa. Primero, no te desanimes: los errores son normales. Segundo, revisa que todas las etiquetas estén cerradas, tanto dentro del div como fuera de él. Tercero, mira el CSS: ¿cada línea termina con punto y coma?

¿Las llaves están abiertas y cerradas? ¿Escribiste bien los nombres de las propiedades? Y cuarto, recuerda que en el CSS, el selector de una clase lleva un punto delante, pero en el HTML no lleva punto. Con esta lista, vas a poder resolver casi cualquier problema.

**[14:15 – 15:00 | Pantalla: Mostrar cómo guardar o compartir el proyecto]**

¡Terminaste tu página de perfil! Ahora quiero que la guardes y la compartas. En CodePen, crea una cuenta gratuita si quieres guardar tu trabajo, y usa el botón Save. Después, copia el enlace de la barra del navegador. Envíaselo a tu familia, a tus amigos, o súbelo al formulario que está en la descripción de este video.

Estoy muy orgulloso de lo que lograste hoy. Combinaste HTML y CSS para crear una página completa, con tu propia información y tus propios colores. Eso es lo que hacen los programadores web todos los días. En la última lección repasaremos los errores comunes y los próximos pasos.

¡Nos vemos allí!

---

## Puntos clave para mostrar en pantalla (anotaciones)
- Primero se planifica con un boceto
- `div` + `class` → agrupar y dar nombre a un bloque
- `.tarjeta` → en CSS, el selector de una clase lleva punto
- `margin: 0 auto;` → centra la tarjeta
- `border-radius: 50%;` → imagen redonda
