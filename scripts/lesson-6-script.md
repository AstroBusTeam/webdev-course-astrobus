# Script — Lección 6: Consejos y próximos pasos (8 min 19 seg)

## Objetivo de la lección
Identificar y corregir errores comunes, conocer buenas prácticas y saber dónde seguir aprendiendo.

## Progreso en la página
Al terminar esta lección, el estudiante sabe encontrar y corregir los errores más comunes, y conoce los recursos para seguir aprendiendo.

## Recursos de la lección
- **Editor en línea:** CodePen
- **Código para practicar:** `/starter-files/lesson-6`
- **Código resuelto:** `/completed-examples/lesson-6`

---

## Guion

**[0:00 – 0:45 | Pantalla: Título y mensaje "¡Lo lograste!"]**

¡Felicitaciones! Lo lograste. Llegaste a la última lección del curso, y ya sabes crear una página web con HTML y CSS. Piensa en todo lo que aprendiste: etiquetas, elementos, atributos, listas, imágenes, enlaces, selectores, colores, bordes, y hasta una página de perfil completa. Hace unas lecciones ni siquiera sabías qué era una etiqueta, y hoy ya construyes páginas por tu cuenta.

Estoy muy orgulloso de ti. En esta lección final, vamos a aprender cómo encontrar y corregir los errores, que es una habilidad fundamental, a conocer algunos buenos hábitos de los programadores, y a descubrir qué puedes aprender después.

**[0:45 – 1:30 | Pantalla: Abrir el código con errores de la lección 6]**

Voy a contarte un secreto: todos los programadores cometen errores. Todos, sin excepción, incluso los más expertos. La diferencia es que los programadores aprenden a encontrarlos y a corregirlos, y eso es lo que haremos ahora. Convirtámonos en detectives de código. Mira esta página: la preparé con siete errores a propósito, cuatro en el HTML y tres en el CSS.

Se ve rara, ¿verdad? Algunas partes no tienen el estilo que debería, y otras están desordenadas. Vamos a revisar el código con atención, como lo haría un detective con su lupa, y a encontrar cada error, uno por uno.

**[1:30 – 3:00 | Pantalla: Resaltar etiquetas sin cerrar]**

Empecemos por el HTML. El primer error, y el más común de todos, son las etiquetas sin cerrar. Mira el título: abrimos la etiqueta h1, escribimos el texto, pero nos olvidamos de cerrarla. Mira ahora el párrafo: tiene su etiqueta p de apertura, pero falta la de cierre.

Y en la lista, el segundo elemento li tampoco está cerrado. Son tres errores del mismo tipo. ¿Y qué pasa cuando no cerramos una etiqueta? El navegador se confunde, y puede mostrar el contenido todo junto, con un tamaño equivocado, o mezclado con otras partes de la página.

Para corregirlo, simplemente agrego la etiqueta de cierre en cada lugar: la h1 con barra, la p con barra, y la li con barra. ¡Mira! La página se ordenó de inmediato. Y fíjate que el editor en línea nos ayudó a verlo, porque el color del código cambia cuando algo no está bien.

Ese es un buen truco para encontrar errores. Una regla de oro: cada vez que abras una etiqueta, ciérrala enseguida, y escribe el contenido en medio. Con este hábito, te vas a ahorrar muchos dolores de cabeza.

```html
<!-- Con errores -->
<h1>Mi página con errores
<p>Este párrafo no está bien cerrado.
<li>Elemento 2
```

```html
<!-- Corregido -->
<h1>Mi página con errores</h1>
<p>Este párrafo no está bien cerrado.</p>
<li>Elemento 2</li>
```

**[3:00 – 3:45 | Pantalla: Resaltar la imagen sin `alt`]**

El cuarto error del HTML está en la imagen. Mira la etiqueta img: tiene el atributo src, con la dirección de la imagen, pero le falta el atributo alt, el texto que la describe. La página se muestra bien, y es posible que no notes el problema, pero no es una buena práctica.

Sin el texto alt, las personas que usan lectores de pantalla no saben qué hay en la imagen. Lo corrijo agregando alt, el signo igual, y entre comillas: Imagen de ejemplo. Un pequeño detalle que hace la diferencia.

```html
<!-- Con error -->
<img src="https://placehold.co/200x150">
```

```html
<!-- Corregido -->
<img src="https://placehold.co/200x150" alt="Imagen de ejemplo">
```

**[3:45 – 4:30 | Pantalla: Resaltar `colour` en el CSS]**

Pasemos al CSS. Mira esta regla del h1. Dice colour, con una u, y no hace nada. ¿Por qué? Porque en CSS la propiedad se escribe sin la u: color. Es un error muy común, porque en algunos idiomas la palabra sí se escribe con u.

Pero el CSS solo entiende las palabras exactas, y si escribes una propiedad con un error, el navegador simplemente la ignora, sin avisarte. Corrijo la palabra: color. ¡Y mira! El título ahora tiene el color que le pedimos. Si un estilo no se aplica, lo primero que debes revisar es que escribiste bien el nombre de la propiedad.

```css
/* Con error */
h1 {
  colour: red;
}
```

```css
/* Corregido */
h1 {
  color: red;
}
```

**[4:30 – 5:30 | Pantalla: Resaltar el punto y coma y la llave faltantes]**

Quedan los dos últimos errores. Mira la regla del body: la primera línea, la del color de fondo, no termina con punto y coma. Sin él, el navegador lee dos propiedades como si fueran una sola, y ninguna funciona. Agrego el punto y coma, ¡y el fondo y el color de letra funcionan!

Y mira la última regla, la del párrafo: abrimos las llaves, escribimos la propiedad, pero nos olvidamos de cerrar las llaves al final. Eso puede hacer que las reglas siguientes dejen de funcionar. Agrego la llave de cierre, y todo vuelve a la normalidad. Ya encontramos los siete errores.

Recuerda: punto y coma al final de cada línea, y las llaves siempre en pareja.

```css
/* Con errores */
body {
  background-color: lightblue
  color: darkblue;
}

p {
  font-size: 18px;
```

```css
/* Corregido */
body {
  background-color: lightblue;
  color: darkblue;
}

p {
  font-size: 18px;
}
```

**[5:30 – 6:30 | Pantalla: Pausa para practicar]**

Ahora es tu turno de ser detective. Abre el enlace de la descripción. Vas a encontrar una página con siete errores distintos, entre HTML y CSS. Tu misión es encontrarlos todos y corregirlos. Te doy algunas pistas. Revisa que cada etiqueta de apertura tenga su cierre.

Busca que las comillas de los atributos estén completas. Comprueba que los nombres de las propiedades CSS estén bien escritos. Y mira si a cada línea de CSS le falta algún punto y coma o alguna llave. Si te trabas, no te preocupes, la solución está disponible en el repositorio.

Y cuando creas que terminaste, pasa tu código por un validador, que es una herramienta que revisa si tu HTML está correcto, y que verás en un momento. Pausa el video y practica ahora. Mucho éxito, detective.

**[6:30 – 7:45 | Pantalla: Lista en pantalla: buenas prácticas]**

Ahora quiero compartirte cuatro hábitos que usan los buenos programadores. Primero, escribe el código ordenado. Usa sangría, es decir, deja espacios al comienzo de las líneas que están dentro de otra etiqueta, para que se vea la estructura, como en un esquema. Segundo, usa comentarios.

Son notas que escribes para ti, que explican qué hace cada parte del código, y que no se ven en la página. En HTML se escriben con un signo menor que, un signo de exclamación y dos guiones. Tercero, guarda y prueba tu página con frecuencia, después de cada cambio pequeño.

Así, si algo falla, sabes exactamente dónde está el problema. Y cuarto, pide ayuda. Preguntar a un compañero, a un profesor o buscar en internet no es hacer trampa, es lo que hacen todos los programadores del mundo. Con estos cuatro hábitos, tu código será más claro, más fácil de corregir y mucho más profesional.

Empieza a practicarlos desde hoy, en cada página que crees.

```html
<!-- Esto es un comentario: no se ve en la página -->
<ul>
  <li>Con sangría, se ve la estructura</li>
</ul>
```

**[7:45 – 8:30 | Pantalla: Mostrar el sitio de documentación web MDN]**

Cuando quieras aprender más, tengo un recurso excelente para ti: la documentación web de MDN, que está disponible en español. Mira esta página. Aquí puedes buscar cualquier etiqueta de HTML o cualquier propiedad de CSS, y te explica para qué sirve, cómo se escribe, y te muestra ejemplos que puedes probar.

Por ejemplo, si quieres saber más sobre la etiqueta img, la buscas aquí, y encuentras todos sus atributos. Es como un diccionario para programadores, y es gratis. Te recomiendo que la guardes en tus favoritos.

**[8:30 – 9:00 | Pantalla: Mostrar el validador de HTML del W3C]**

Y otra herramienta muy útil es el validador de HTML. Es una página en línea, donde pegas tu código, y revisa automáticamente si hay errores. Te avisa qué línea tiene el problema y por qué. Es como tener un detective que revisa tu trabajo por ti.

Úsalo cuando termines una página, para estar seguro de que todo está correcto antes de compartirla con los demás.

**[9:00 – 9:30 | Pantalla: Línea de ruta: HTML, CSS, luego JavaScript]**

¿Y qué sigue después? Ya dominas la estructura con HTML y el estilo con CSS. El siguiente paso en el camino se llama JavaScript. Es el lenguaje que le da vida a las páginas: permite crear botones que hacen cosas, juegos, animaciones y mucho más.

Si HTML es la estructura, y CSS es la decoración, JavaScript es la electricidad que hace que todo funcione.

**[9:30 – 10:00 | Pantalla: Mostrar el formulario para compartir y el cuestionario]**

Para terminar, tengo dos invitaciones. La primera: comparte tu página de perfil con nosotros en el formulario que está en la descripción de este video. Nos encantará verla. Y la segunda: pon a prueba lo que aprendiste con el cuestionario final, que tiene diez preguntas sencillas.

¡Muchas gracias por acompañarme en este curso! Fue un placer ser tu guía. Sigue practicando, sigue creando, y sobre todo, sigue divirtiéndote. ¡Hasta pronto!

---

## Puntos clave para mostrar en pantalla (anotaciones)
- Errores comunes: etiquetas sin cerrar, `alt` faltante, propiedad mal escrita, `;` o `}` faltantes
- Cuatro hábitos: código ordenado, comentarios, guardar y probar seguido, pedir ayuda
- MDN → documentación web en español
- Validador de HTML → revisa tu código
- Siguiente paso → JavaScript
