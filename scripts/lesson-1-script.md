# Script — Lección 1: ¿Qué es el desarrollo web? (3:46 min)

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

**[0:00 – 0:25 | Pantalla: Título: "¿Qué es el desarrollo web?" con animación sencilla]**

¡Hola, bienvenido, bienvenida! Soy tu guía en este curso y voy a acompañarte en cada lección. ¿Alguna vez te has preguntado cómo se crea una página web? ¿Cómo hacen los programadores para que aparezcan botones, imágenes y colores en la pantalla? Hoy empieza tu camino para descubrirlo, y no necesitas instalar absolutamente nada.

Solo tu navegador y muchas ganas de aprender. ¡Empecemos!

**[0:25 – 1:02 | Pantalla: Capturas de 3 sitios distintos (una tienda, un sitio de videos, un blog)]**

Cada vez que abres una página en tu celular o en tu computadora, estás viendo un sitio web. Fíjate en estos tres ejemplos. Aquí tenemos una tienda, donde puedes ver productos y precios. Aquí hay un sitio de videos, con botones para reproducir y pausar.

Y aquí tenemos un blog, con textos y fotos que alguien escribió para compartir con el mundo. Se ven muy distintos entre sí, ¿verdad? Pero tienen algo en común: todos están construidos con las mismas piezas básicas. Hoy vas a descubrir cuáles son, y verás que no son tan misteriosas como parecen.

**[1:02 – 1:30 | Pantalla: Dibujo de una casa: estructura a la izquierda, casa pintada y decorada a la derecha]**

Para entenderlo mejor, imagina una casa. Primero se levantan las paredes, el techo y las habitaciones. Esa es la estructura. Después llega el momento divertido: pintar, elegir los colores, poner cortinas y decorar el jardín. Esa es la decoración. Una página web funciona exactamente igual: primero se construye la estructura, y luego se le da estilo.

¡Es una idea muy sencilla!

**[1:30 – 2:09 | Pantalla: Etiquetas en pantalla: HTML = contenido y estructura, CSS = estilo y diseño]**

Las dos piezas se llaman HTML y CSS. El HTML es la estructura: se encarga del contenido, o sea, los títulos, los textos, las imágenes y los enlaces. Es como las paredes y las habitaciones de la casa. El CSS es el estilo: se encarga del diseño, es decir, los colores, las letras, los bordes y el orden de todo.

Es como la pintura y la decoración. Recuerda esta fórmula: un sitio web es igual a contenido más estilo. El contenido se escribe con HTML, y el estilo se escribe con CSS.

**[2:09 – 2:41 | Pantalla: Abrir CodePen con el código de la lección 1, resaltar la zona de HTML, luego la de CSS]**

Veamos esto en vivo. Estamos en CodePen, un editor en línea y gratuito que funciona directamente en tu navegador. No tienes que descargar ningún programa ni crear una cuenta para practicar. Aquí tenemos una página muy sencilla, con un título y dos párrafos de texto.

Vamos a explorarla juntos, paso a paso, sin prisa, y verás que nada de esto es complicado.

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

**[2:41 – 2:55 | Pantalla: Cambiar white por yellow y mostrar el resultado]**

Veamos qué pasa si cambio esa línea. Borro la palabra white, que significa blanco en inglés, y escribo yellow, que significa amarillo. ¡Mira esto! La página cambió de color al instante. ¿Notaste que no toqué el contenido? Solo cambié el estilo. Eso es exactamente lo que hace el CSS, y eso es lo que vas a hacer tú ahora mismo.

```css
body {
  background-color: lightyellow;
}
```

**[2:55 – 3:18 | Pantalla: Pausa para practicar: cartel "Pausa el video"]**

Ahora te toca a ti. Abre el enlace que está en la descripción de este video. Busca la línea del color de fondo y cámbiala por el color que más te guste. Puedes probar con red, que significa rojo, con skyblue, que significa celeste, o con pink, que significa rosado.

Cuando termines, regresa para el resumen final. Pausa el video y practica ahora.

**[3:18 – 3:46 | Pantalla: Resumen: HTML = contenido, CSS = estilo]**

¡Muy bien! Terminamos la primera lección. Hoy aprendiste que un sitio web está hecho de dos piezas principales: el HTML, que pone el contenido y la estructura, y el CSS, que pone el estilo y el diseño. También usaste un editor en línea y cambiaste el color de una página real.

¡Eso ya es programar! En la próxima lección vas a escribir tu primera página con HTML desde cero. ¡Nos vemos allí!

---

## Puntos clave para mostrar en pantalla (anotaciones)
- HTML → contenido y estructura
- CSS → estilo y diseño
- Sitio web = contenido + estilo
- `background-color` → cambia el color de fondo
