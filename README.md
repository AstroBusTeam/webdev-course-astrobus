# Fundamentos de Desarrollo Web: código fuente del curso

Curso introductorio de **HTML y CSS** para estudiantes de secundaria (12 a 17 años) que nunca han programado. Dura aproximadamente 1 hora y se divide en 6 lecciones en video.

📄 **Plan del curso** (lecciones, videos y enlaces a las prácticas): [course-plan.md](course-plan.md)

---

## ¿Necesito instalar algo?

**No.** Solo necesitas un navegador web (Chrome, Firefox, Safari o Edge). Todas las prácticas se hacen en **CodePen**, un editor de código gratuito que funciona dentro del navegador.

---

## Cómo seguir el curso

1. **Mira la lección** en YouTube. El enlace de cada video está en el [plan del curso](course-plan.md).
2. **Abre la práctica en CodePen.** El enlace está en la descripción de cada video y en el plan del curso.
3. **Escribe tu código** en los paneles de CodePen:
   - Panel **HTML**: el contenido de la página.
   - Panel **CSS**: el estilo de la página.
4. **Compara con la solución** si te trabas. Cada lección tiene un enlace con el código resuelto.

> Puedes practicar sin crear una cuenta. Si quieres guardar tu trabajo y compartir el enlace, crea una cuenta gratuita en CodePen.

---

## Contenido del repositorio

| Carpeta o archivo | Qué contiene |
|---|---|
| `course-plan.md` | Plan del curso: resumen, secuencia de lecciones, enlaces a los videos y a las prácticas |
| `starter-files/` | **Código de partida** de cada lección: lo que el estudiante tiene antes de empezar a practicar |
| `completed-examples/` | **Código resuelto** de cada lección: el resultado final, para comparar |
| `scripts/` | Guiones de los videos: qué se muestra en pantalla y qué se dice en cada momento |
| `quiz.md` | Preguntas del cuestionario final, con sus respuestas |

Dentro de `starter-files/`, `completed-examples/` y `scripts/` hay un elemento por cada lección (`lesson-1` a `lesson-6`).

### ¿Cuál es la diferencia entre `starter-files` y `completed-examples`?

Son el **mismo ejercicio en dos momentos distintos**:

- **`starter-files`** es el ejercicio antes de resolverlo, con los espacios por completar.
- **`completed-examples`** es el ejercicio ya resuelto.

La diferencia entre ambos es justo lo que se aprende en esa lección. Por ejemplo, en la lección 2 el código de partida tiene el `body` vacío, y el código resuelto agrega un título `h1` y un párrafo `p`.

---

## Lecciones

| # | Lección | Duración | Qué se aprende |
|---|---|---|---|
| 1 | ¿Qué es el desarrollo web? | 5 min 11 seg | De qué está hecho un sitio web: HTML y CSS |
| 2 | Introducción a HTML | 8 min 2 seg | Etiquetas, elementos, atributos y estructura básica |
| 3 | Añadir más elementos HTML | 6 min 58 seg | Encabezados, listas, imágenes y enlaces |
| 4 | Introducción a CSS | 9 min 49 seg | Selectores, colores, fuentes, bordes y centrado |
| 5 | Crear una página web sencilla | 12 min 21 seg | Una página de perfil personal completa |
| 6 | Consejos y próximos pasos | 8 min 19 seg | Errores comunes, buenos hábitos y cómo seguir aprendiendo |

---

## Ejercicios y retos

Cada lección tiene dos tipos de práctica, que se explican en `starter-files/lesson-N/README.md`:

| Tipo | Qué es | ¿Es obligatorio? |
|---|---|---|
| **Ejercicio guiado** | Se hace durante el video, en la pausa para practicar | Sí |
| **Reto extra** | Un ejercicio adicional, un poco más difícil, para quien quiere practicar más | No |

Las soluciones explicadas están en `completed-examples/lesson-N/README.md`.

| # | Reto extra |
|---|---|
| 1 | Personalizar el título y sus colores |
| 2 | Ficha de tu animal favorito |
| 3 | Mi receta favorita, con listas con viñetas y numeradas |
| 4 | Darle estilo a la receta |
| 5 | Un perfil con dos tarjetas que reutilizan una misma clase |
| 6 | Detective de código: una página con 7 errores por corregir |

---

## Cuestionario

Las preguntas del cuestionario final, con sus respuestas, están en [quiz.md](quiz.md).
