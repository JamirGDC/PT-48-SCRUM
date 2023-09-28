## Digrama de fluyo de una retrospectiva Scrum, según mi punto de vista

![Diagrama de flujo de una retrospectiva](https://raw.githubusercontent.com/JamirGDC/PT-48-SCRUM/main/graph.png)

## Programacion Imperativa o declarativa

La programación puede ser imperativa o declarativa. En la programación imperativa, se especifica una secuencia de operaciones a realizar para alcanzar un objetivo. Los lenguajes de programación imperativos incluyen PHP, Python y JavaScript. En la programación declarativa, se especifica el resultado deseado, no cómo lograrlo. Los lenguajes de programación declarativos incluyen SQL y Prolog. 

La programación declarativa tiene la ventaja de ser más fácil de leer y entender, ya que se enfoca en el qué en lugar del cómo. Además, puede ser más fácil de optimizar y depurar. Por otro lado, la programación imperativa puede ser más eficiente en términos de rendimiento y puede ser más adecuada para problemas complejos que requieren un control detallado del flujo de ejecución. 



## -   Lenguajes de programacion basado en C y cuales son los mas usados

Existen varios lenguajes de programación basados en C, como C++, C#, Objective-C, Vala, D, Go, Rust, entre otros. C es un lenguaje de programación de propósito general originalmente desarrollado por Dennis Ritchie entre 1969 y 1972 en los Laboratorios Bell, como evolución del anterior lenguaje B, a su vez basado en BCPL. 

En cuanto a los lenguajes de programación más utilizados, según diferentes índices, se encuentran Python, Java, JavaScript, C#, PHP, C/C++, R, entre otros. C y C++ siguen siendo muy utilizados en el desarrollo de sistemas operativos, juegos, aplicaciones de escritorio y otros proyectos que requieren un control detallado del hardware y la memoria. 


## Lenguajes de programación interpretados y compilados

Los lenguajes de programación se pueden clasificar en dos categorías principales: lenguajes interpretados y lenguajes compilados. En un lenguaje compilado, el código fuente se traduce directamente a código de máquina por medio de un compilador, lo que genera un archivo ejecutable que se puede ejecutar en la máquina de destino. En cambio, en un lenguaje interpretado, el código fuente se ejecuta línea por línea por medio de un intérprete, que lee el código fuente y lo ejecuta en tiempo real.

Algunos ejemplos de lenguajes compilados son C, C++, Java, Go y Rust, mientras que algunos ejemplos de lenguajes interpretados son Python, Ruby y JavaScript. Los lenguajes compilados suelen ser más rápidos y eficientes que los lenguajes interpretados, ya que el código se traduce directamente a código de máquina. Sin embargo, los lenguajes interpretados son más flexibles y fáciles de usar, ya que no requieren un paso de compilación adicional.

## Diferencias entre var y let

En JavaScript, `var` y `let` son palabras clave utilizadas para declarar variables. La principal diferencia entre ellas es el alcance de las variables que crean. Las variables declaradas con `var` tienen un alcance de función, lo que significa que están disponibles en todo el cuerpo de la función en la que se declaran. Por otro lado, las variables declaradas con `let` tienen un alcance de bloque, lo que significa que solo están disponibles dentro del bloque en el que se declaran.

Por ejemplo, si declaramos una variable `x` dentro de un bloque `if` utilizando `let`, esa variable solo estará disponible dentro de ese bloque `if`. Si declaramos la misma variable `x` dentro del mismo bloque `if` utilizando `var`, esa variable estará disponible en todo el cuerpo de la función en la que se encuentra el bloque `if`.

Además, las variables declaradas con `let` no pueden ser redeclaradas dentro del mismo alcance, mientras que las variables declaradas con `var` sí pueden ser redeclaradas. Esto puede llevar a errores difíciles de detectar en el código.

## Diferencias entre ""| '' | ``

En JavaScript, las comillas simples (`'`), las comillas dobles (`"`) y las comillas invertidas o backticks (`` ` ``) se utilizan para definir strings o cadenas de texto. La principal diferencia entre ellas es que las comillas invertidas permiten la interpolación de variables y expresiones dentro del string, mientras que las comillas simples y dobles no lo permiten.

Por ejemplo, si queremos definir un string que contenga el nombre de una persona, podemos hacerlo de la siguiente manera:

```
let nombre = 'Juan';
let saludo = `Hola, ${nombre}!`;
```

En este caso, utilizamos las comillas invertidas para definir el string `saludo`, y dentro de él interpolamos la variable `nombre` utilizando la sintaxis `${nombre}`. Esto nos permite crear strings más complejos y dinámicos.

Por otro lado, las comillas simples y dobles se utilizan de manera intercambiable para definir strings que no requieren interpolación. No hay una diferencia significativa entre ellas, aunque algunas personas prefieren utilizar comillas simples para strings y comillas dobles para atributos HTML, por ejemplo.
