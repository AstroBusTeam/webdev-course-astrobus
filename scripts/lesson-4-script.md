# Script — Lección 4: Introducción a CSS (9 min 49 seg)

## Objetivo de la lección
Escribir reglas CSS con selector, propiedad y valor para cambiar colores, fuentes, bordes y la alineación del texto.

## Progreso en la página
Al terminar esta lección, la página tiene fondo de color, fuente propia, texto centrado, título en azul, imagen con borde redondeado y enlaces de otro color.

## Recursos de la lección
- **Editor en línea:** CodePen
- **Código para practicar:** `/starter-files/lesson-4`
- **Código resuelto:** `/completed-examples/lesson-4`

---

## Guion

**[0:00 – 0:45 | Pantalla: Título y página sin estilo]**

¡Hola otra vez! Mira la página que construimos en la lección anterior. Tiene un título, una lista, una imagen y un enlace. Todo el contenido está ahí, pero seamos sinceros: se ve un poco aburrida, con letras negras sobre un fondo blanco. ¿Y si pudiéramos darle color, cambiar las letras, poner bordes y centrar todo?

Eso es justamente lo que vamos a hacer hoy con CSS. Al terminar esta lección, tu página se va a ver mucho más atractiva, y lo mejor es que tú mismo vas a decidir cómo se ve. Prepárate para sacar al artista que llevas dentro.

**[0:45 – 1:30 | Pantalla: Mostrar el panel CSS del editor]**

Estamos de nuevo en CodePen. Fíjate que, además del panel del HTML, tenemos este otro panel, que dice CSS. Aquí es donde escribimos el estilo de la página. El HTML y el CSS siempre van separados: en un lugar está el contenido, y en otro, el estilo.

Así, si quieres cambiar los colores, no necesitas tocar el contenido. En un proyecto con archivos, el CSS se guarda en un archivo aparte, y se conecta con el HTML. Pero en este editor en línea, todo está listo y conectado. Solo tenemos que escribir en el panel correcto.

**[1:30 – 2:30 | Pantalla: Esquema: `selector { propiedad: valor; }` con colores]**

El CSS se escribe con reglas, y todas las reglas tienen la misma forma. Mira las tres piezas de este rompecabezas. La primera, la naranja, es el selector. Le dice al navegador a qué elemento le vamos a dar estilo: por ejemplo, a los títulos h1, a las imágenes, o a toda la página.

Después se abren unas llaves, y dentro de ellas van las otras dos piezas. La celeste es la propiedad: lo que queremos cambiar, como el color o la fuente. Y la amarilla es el valor: cómo lo queremos cambiar, como rojo o azul. Entre la propiedad y el valor van dos puntos, y al final de cada línea va un punto y coma.

Y las llaves se cierran al terminar. Selector, propiedad y valor: son las tres piezas que debes recordar.

```css
selector {
  propiedad: valor;
}
```

**[2:30 – 3:30 | Pantalla: Escribir `body { background-color: #f0f8ff; }`]**

Empecemos con el color de fondo de toda la página. Para esto, el selector es body, que, como ya sabes, es el cuerpo de la página. Escribo body, y abro las llaves. Dentro, escribo la propiedad: background-color, que significa color de fondo en inglés. Después, dos puntos, y el valor.

Voy a usar un código de color, que empieza con el signo numeral, y que en este caso es un azul muy clarito. Cierro con un punto y coma, y luego cierro las llaves. ¡Mira cómo cambió toda la página! Ya no es blanca, tiene un suave tono azulado.

Y así de fácil es cambiarle el fondo. Si prefieres, también puedes usar nombres de colores en inglés, como lightblue, que significa azul claro, o lightgreen, que significa verde claro.

```css
body {
  background-color: #f0f8ff;
}
```

**[3:30 – 4:30 | Pantalla: Escribir `h1 { color: #1e3a8a; }`]**

Ahora vamos a cambiarle el color al título. Esta vez, el selector es h1, que es el elemento que queremos estilizar. Abro las llaves y escribo la propiedad color, que cambia el color de las letras. Después, dos puntos, y un código de azul oscuro.

Cierro con el punto y coma. ¡Mira cómo cambió! El título ahora es de un azul fuerte y elegante. Fíjate que el selector h1 afecta a todos los títulos h1 de la página, y no a los demás elementos. Eso es lo bueno del CSS: con una sola regla, le das estilo a todos los elementos del mismo tipo.

Puedes escribir los colores con nombres, como red o blue, o con códigos, que te dan muchísimos más tonos.

```css
h1 {
  color: #1e3a8a;
}
```

**[4:30 – 5:30 | Pantalla: Pausa para practicar 1]**

Ahora te toca a ti. Abre el enlace de la descripción. Vas a encontrar la página de la lección anterior, con el panel de CSS vacío. Tu primer reto es escribir dos reglas. La primera, con el selector body, para cambiar el color de fondo de la página.

La segunda, con el selector h1, para cambiar el color del título. Escoge los colores que quieras, y pruébalos hasta que te gusten. Si no recuerdas la forma de una regla, vuelve a mirar el rompecabezas: selector, llaves, propiedad, dos puntos, valor y punto y coma.

Si algo no cambia en la pantalla, revisa que escribiste bien la propiedad y que no olvidaste el punto y coma. Pausa el video y practica ahora. Te espero.

**[5:30 – 6:30 | Pantalla: Escribir `font-family: Arial, sans-serif;` en el `body`]**

¡Bienvenido de nuevo! Sigamos con las letras. Para cambiar el tipo de letra, usamos la propiedad font-family, que significa familia de fuente. La voy a escribir dentro de la regla del body, para que se aplique a toda la página. Escribo font-family, dos puntos, y el valor: Arial, una coma, y sans-serif.

¿Por qué escribo dos valores? Porque el primero es la fuente que queremos usar, y el segundo es una opción de respaldo, por si la primera no está disponible en la computadora de quien visita tu página. Y de nuevo cierro con el punto y coma.

Mira cómo cambió el tipo de letra de todo el texto. Ahora se ve más moderno.

```css
body {
  background-color: #f0f8ff;
  font-family: Arial, sans-serif;
}
```

**[6:30 – 7:30 | Pantalla: Escribir `text-align: center;`]**

Ahora vamos a centrar el contenido. Sigo dentro de la regla del body y escribo la propiedad text-align, que significa alineación del texto. El valor es center, que en inglés significa centro. Escribo el punto y coma, y... ¡todo el texto de la página se centró!

El título, el párrafo y la lista ahora están justo en el medio. Si prefieres otra posición, puedes probar con left, que significa izquierda, o con right, que significa derecha. Prueba los tres valores y mira la diferencia. Es una manera muy rápida de ordenar tu página.

Centrar el contenido le da un aspecto mucho más limpio. Fíjate que, igual que antes, escribí una sola propiedad nueva dentro de la misma regla del body, y esa sola línea cambió la página completa.

```css
body {
  background-color: #f0f8ff;
  font-family: Arial, sans-serif;
  text-align: center;
}
```

**[7:30 – 9:00 | Pantalla: Escribir `img { border: 4px solid #2563eb; border-radius: 10px; }`]**

Vamos a darle un toque especial a la imagen. Escribo un nuevo selector: img, y abro las llaves. Ahora, la propiedad border, que significa borde. Para un borde necesitamos tres datos, y los escribimos en una sola línea, separados por espacios. El primero es el grosor: voy a usar cuatro píxeles.

El segundo es el tipo de línea: voy a usar solid, que significa línea continua. Y el tercero es el color: un azul que combine con nuestro título. Cierro con el punto y coma. ¡Mira! Ahora la imagen tiene un marco azul que la resalta.

Pero todavía se ve un poco cuadrada. Vamos a redondearla. Escribo otra propiedad: border-radius, que significa radio del borde. El valor es diez píxeles. Las esquinas se suavizaron, y la imagen se ve más amigable y moderna. Puedes probar con un valor más alto, como cincuenta píxeles, y verás cómo se redondea todavía más.

Juega con los números y escoge el que más te guste. Recuerda que la regla del img tiene dos propiedades, border y border-radius, y que cada una termina con su propio punto y coma.

```css
img {
  border: 4px solid #2563eb;
  border-radius: 10px;
}
```

**[9:00 – 9:30 | Pantalla: Escribir `a { color: #dc2626; }`]**

Por último, los enlaces. Con el selector a, que es la etiqueta de los enlaces, escribo la propiedad color, y le doy un tono rojo. ¡Mira! El enlace ahora tiene un color vivo que llama la atención. Con esto, ya le diste estilo a casi todos los elementos de tu página, y fíjate cuánto cambió con apenas unas pocas reglas.

```css
a {
  color: #dc2626;
}
```

**[9:30 – 11:00 | Pantalla: Pausa para practicar 2]**

Es el turno de tu segunda práctica. Esta vez vas a agregar más estilos a tu página. Primero, dentro de la regla del body, agrega la propiedad font-family para elegir un tipo de letra, y text-align con el valor center, para centrar el texto. Segundo, crea una regla nueva con el selector img, y escribe un borde con la propiedad border, usando un grosor, un tipo de línea y un color.

Después, agrega border-radius para redondear las esquinas. Tercero, si te animas, cambia el color de los enlaces con el selector a. Si algo no funciona, revisa los puntos y comas y las llaves, porque son los errores más comunes. Y no tengas miedo de experimentar: cambia los valores, mira qué pasa, y deshaz lo que no te guste.

Así es como aprenden los programadores. Para quienes quieran un reto extra, intenten darle estilo a toda una receta, con títulos de colores y líneas debajo. Cuando termines, compara tu resultado con la solución del repositorio para ver si quedó parecido. Pausa el video y practica ahora.

**[11:00 – 11:30 | Pantalla: Mostrar el resultado final]**

Mira cómo quedó nuestra página. A la izquierda, cómo se veía al principio de la lección: simple, con fondo blanco y letras negras. Y a la derecha, cómo se ve ahora: con fondo de color, un título azul, texto centrado, una imagen con marco redondeado y un enlace rojo.

Es la misma página, con el mismo contenido. Lo único que cambió fue el estilo, y eso lo hiciste tú con CSS.

**[11:30 – 12:00 | Pantalla: Resumen: selector, propiedad, valor]**

¡Felicitaciones! Hoy aprendiste a escribir reglas CSS, formadas por un selector, una propiedad y un valor. Cambiaste colores de fondo y de letras, elegiste una fuente, centraste el texto y le pusiste un borde redondeado a una imagen. ¡Ya sabes dar estilo a una página web!

En la próxima lección vamos a juntar todo lo que aprendiste para crear una página completa de perfil personal. ¡Será muy divertido! Nos vemos ahí.

---

## Puntos clave para mostrar en pantalla (anotaciones)
- Regla CSS: `selector { propiedad: valor; }`
- `background-color` y `color` → colores
- `font-family` → tipo de letra
- `text-align` → alineación del texto
- `border` y `border-radius` → borde y esquinas redondeadas
