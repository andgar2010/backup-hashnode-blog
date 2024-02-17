---
title: "Buenas prácticas para nombrar las variables de forma modular"
datePublished: Wed Oct 19 2022 00:00:00 GMT+0000 (Coordinated Universal Time)
cuid: clsm2dwxi000109kv0lyyga75
slug: buenas-practicas-para-nombrar-las-variables-de-forma-modular

---

# Estándar nombramiento las variables de forma modular

Cuando trabajas con un lenguaje de programación, es necesario aprovechar el poder de las variables. Sin embargo, si creas nombres de variables espontáneamente a medida que programas, lo más probable es que tu convención de nomenclatura carezca de cohesión. Deberías pensar en organizar los nombres de tus variables (y del proyecto en general) de forma modular. Esto aportará estructura y unidad a tu proyecto en su conjunto, lo que facilitará su comprensión y navegación.

## Una sugerencia de nomenclatura

Digamos que necesitas una variable para el color del texto en tu proyecto. ¿Deberías llamarla `text-color` o `color-text`? ¿Cómo se decide? Elegir uno al azar puede contribuir a la falta de estructura a medida que aumenta el número de variables en tu proyecto. Como se ha comprobado en la práctica, a menudo olvidamos exactamente cómo hemos nombrado las variables para determinados proyectos, lo que puede llevar a la confusión y a métodos de búsqueda y sustitución global de nombres de variables que llevan mucho tiempo.

Lo que necesitamos es una regla para definir y seleccionar nuestros nombres de variables. Una excelente manera de mantener la modularidad en tu proyecto es agrupar las variables que comparten relaciones y puntos en común. Entonces, puedes nombrarlas ordenando las palabras que describen su función de **genérico a específico de izquierda a derecha**.

Por ejemplo, si tienes cuatro variables para cuatro colores de borde diferentes, puedes nombrarlas todas comenzando por `border` (ya que es el término genérico que todas comparten) y ser más específico con una lectura de izquierda a derecha. Agrupar y nombrar las variables de esta manera hace que tu código sea más fácil de leer, comprender y recordar.

### Sin patrón (No debe utilizar este ejemplo)

| Dart / TypeScript | CSS |
| --- | --- |
| `// Dart / TypeScript class Style { ... var blueBorder; var lightBlueBorder; var lightestBlueBorder; var darkGreenBorder; var darkestBorderGreen; var redBorder; ... }` | `/* CSS */ :root { ... --blue-border; --light-blue-border; --lightest-blue-border; --dark-green-border; --darkest-border-green; --red-border; ... }` |

### Genérico -&gt; Específico (Se recomienda utilizar este ejemplo)

| Dart / TypeScript | CSS |
| --- | --- |
| `// Dart / TypeScript class Style { ... var borderBlue; var borderBlueLight; var borderBlueLightest; var borderGreenDark; var borderGreenDarkest; var borderRed; ... }` | `/* CSS */ :root { ... --border-blue; --border-blue-light; --border-blue-lightest; --border-green-dark; --border-green-darkest; --border-red; ... }` |

## De lo más general a lo más específico: Un ejemplo

Continúe este artículo en mi blog personal [aquí](https://tech-andgar.me/es/posts/buenas-pr%C3%A1cticas-para-nombrar-las-variables-de-forma-modular/).