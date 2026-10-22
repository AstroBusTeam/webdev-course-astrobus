# Script — Lección 1: ¿Qué es el desarrollo web? (5:10 min)

## Objetivo de la lección
Entender de qué está hecho un sitio web y distinguir qué hace HTML y qué hace CSS.

## Progreso en la página
Al terminar esta lección, el estudiante conoce las dos piezas de un sitio web (HTML y CSS) y ya cambió el color de fondo de una página desde el CSS. Es el punto de partida del curso.

## Recursos de la lección
- **Editor en línea:** CodePen
- **Código para practicar:** `/starter-files/lesson-1`
- **Código resuelto:** `/completed-examples/lesson-1`

---

## Guion

**[0:00 – 0:50 | Pantalla: Título: "¿Qué es el desarrollo web?" con animación sencilla]**

¡Hola, bienvenido, bienvenida! Soy tu guía en este curso y voy a acompañarte en cada lección. ¿Alguna vez te has preguntado cómo se crea una página web? ¿Cómo hacen los programadores para que aparezcan botones, imágenes y colores en la pantalla? Hoy empieza tu camino para descubrirlo, y no necesitas instalar absolutamente nada.

Solo tu navegador y muchas ganas de aprender. Te cuento rápido cómo funciona este curso. Son seis lecciones cortas. En la primera descubrirás de qué está hecho un sitio web. Después aprenderás HTML, que da la estructura, y CSS, que da el estilo. Al final, juntarás todo para crear tu propia página de perfil.

Cada lección tiene una práctica con un enlace en la descripción, y puedes pausar el video cuando quieras. ¡Empecemos!

**[0:50 – 1:27 | Pantalla: Capturas de 3 sitios distintos (una tienda, un sitio de videos, un blog)]**

Cada vez que abres una página en tu celular o en tu computadora, estás viendo un sitio web. Fíjate en estos tres ejemplos. Aquí tenemos una tienda, donde puedes ver productos y precios. Aquí hay un sitio de videos, con botones para reproducir y pausar.

Y aquí tenemos un blog, con textos y fotos que alguien escribió para compartir con el mundo. Se ven muy distintos entre sí, ¿verdad? Pero tienen algo en común: todos están construidos con las mismas piezas básicas. Hoy vas a descubrir cuáles son, y verás que no son tan misteriosas como parecen.

**[1:27 – 1:55 | Pantalla: Dibujo de una casa: estructura a la izquierda, casa pintada y decorada a la derecha]**

Para entenderlo mejor, imagina una casa. Primero se levantan las paredes, el techo y las habitaciones. Esa es la estructura. Después llega el momento divertido: pintar, elegir los colores, poner cortinas y decorar el jardín. Esa es la decoración. Una página web funciona exactamente igual: primero se construye la estructura, y luego se le da estilo.

¡Es una idea muy sencilla!

**[1:55 – 2:48 | Pantalla: Etiquetas en pantalla: HTML = contenido y estructura, CSS = estilo y diseño]**

Las dos piezas se llaman HTML y CSS. El HTML es la estructura: se encarga del contenido, o sea, los títulos, los textos, las imágenes y los enlaces. Es como las paredes y las habitaciones de la casa. El CSS es el estilo: se encarga del diseño, es decir, los colores, las letras, los bordes y el orden de todo.

Es como la pintura y la decoración. Recuerda esta fórmula: un sitio web es igual a contenido más estilo. El contenido se escribe con HTML, y el estilo se escribe con CSS. Piénsalo así: si quitas el CSS, la página sigue ahí, con todo su contenido, pero sin colores ni orden.

Y si quitas el HTML, no queda nada que decorar. Las dos piezas se necesitan.

**[2:48 – 3:51 | Pantalla: Abrir CodePen con el código de la lección 1, resaltar la zona de HTML, luego la de CSS]**

Veamos esto en vivo. Estamos en CodePen, un editor en línea y gratuito que funciona directamente en tu navegador. No tienes que descargar ningún programa ni crear una cuenta para practicar. Aquí tenemos una página muy sencilla, con un título y dos párrafos de texto.

Vamos a explorarla juntos, paso a paso, sin prisa, y verás que nada de esto es complicado. Mira cómo está organizada la pantalla. Arriba están los paneles donde se escribe el código. Abajo está el resultado: la página tal como la verían las personas. Cada cambio que hagas en el código se refleja ahí en segundos, sin guardar ni actualizar nada.

Este primer panel es el del HTML. Aquí está el contenido: un título que dice Esto es HTML, y dos párrafos con texto. Ahora mira este otro panel, el del CSS. Aquí está el estilo de la página. Fíjate que, por ahora, solo tiene una regla que le dice al navegador cuál es el color de fondo.

Ahora es blanco, y por eso la página se ve blanca.

```html
<h1>Esto es HTML</h1>
<p>El HTML pone el contenido: títulos, textos e imágenes.</p>
<p>El CSS le da el estilo: colores, fuentes y orden.</p>
```

```css
body {
  background-color: white;
}
```

**[3:51 – 4:05 | Pantalla: Cambiar white por yellow y mostrar el resultado]**

Veamos qué pasa si cambio esa línea. Borro la palabra white, que significa blanco en inglés, y escribo yellow, que significa amarillo. ¡Mira esto! La página cambió de color al instante. ¿Notaste que no toqué el contenido? Solo cambié el estilo. Eso es exactamente lo que hace el CSS, y eso es lo que vas a hacer tú ahora mismo.

```css
body {
  background-color: lightyellow;
}
```

**[4:05 – 4:42 | Pantalla: Pausa para practicar: cartel "Pausa el video"]**

Ahora te toca a ti. Abre el enlace que está en la descripción de este video. Busca la línea del color de fondo y cámbiala por el color que más te guste. Puedes probar con red, que significa rojo, con skyblue, que significa celeste, o con pink, que significa rosado.

Si terminas rápido, te dejo un reto: cambia también el texto del título. Borra las palabras Esto es HTML y escribe tu nombre. Esto se hace en el panel del HTML, porque cambias el contenido y no el estilo. Cuando termines, regresa para el resumen final.

Pausa el video y practica ahora.

**[4:42 – 5:10 | Pantalla: Resumen: HTML = contenido, CSS = estilo]**

¡Muy bien! Terminamos la primera lección. Hoy aprendiste que un sitio web está hecho de dos piezas principales: el HTML, que pone el contenido y la estructura, y el CSS, que pone el estilo y el diseño. También usaste un editor en línea y cambiaste el color de una página real.

¡Eso ya es programar! En la próxima lección vas a escribir tu primera página con HTML desde cero. ¡Nos vemos allí!

---

## Puntos clave para mostrar en pantalla (anotaciones)
- HTML → contenido y estructura
- CSS → estilo y diseño
- Sitio web = contenido + estilo
- `background-color` → cambia el color de fondo
