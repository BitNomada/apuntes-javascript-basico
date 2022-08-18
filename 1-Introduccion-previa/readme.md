
## Información previa
### ¿Qué es JavaScript? Características más importantes
JavaScript es un lenguaje de programación **interpretado**, es decir, que no requiere de un compilador para poder ejecutarse.

Es un lenguaje que se va a ejecutar normalmente en el navegador web, aunque también se puede usar como lenguaje de backend con **Node.js**

Sus **características más importantes** son:

 - Es un lenguaje que se ejecuta en el cliente normalmente.
 - Lenguaje orientado a objetos
 - Lenguaje de tipado débil
 - Lenguaje de alto nivel
 - Lenguaje interpretado
 - Muy utilizado hoy en día
 
Si quieres más información sobre qué es JavaScript, tienes un enlace en los **enlaces de interés**. Pero supongo que si has llegado a este repositorio, ya sabes qué es JavaScript y por qué debes/quieres aprenderlo.

### Requisitos recomendados 
Podríamos usar un simple bloc de notas para programar JavaScript o para seguir estos apuntes.

No obstante os recomiendo usar un IDE como es [Visual Studio Code](https://code.visualstudio.com/download) (VSCode) en el que le podemos instalar varios complementos para hacernos la vida más fácil y tener además diferentes herramientas disponibles (debugger, terminal...).

Así que os recomiendo instalaros el **IDE de VSCode** e instalar los siguientes plugins:

 - ES6 JavaScript Code Snippets
 - Prettier
 - Bracket Pair Colorizer
 - Ident-Rainbow
 - Quokka.js
 - Live Server

Otra opción es utilizar un **editor online** como es [Playcode](https://playcode.io/javascript-online), el cual tiene ya bastantes extensiones instaladas bastante interesantes y un terminal. 

Aunque si quieres ir iniciándote ya a los entornos de desarrollo que se utilizan en las empresas y proyectos reales, instálate VSCode y Node.js

### Ejecutar JavaScript

Para **ejecutar JavaScript** y ver cómo se comporta nuestro código, lo más común es hacerlo de las siguientes formas:

 - Ejecutar JavaScript y mostrarlo en HTML
 - Usar el terminal del navegador para ejecutar nuestro código (click derecho -> inspeccionar -> terminal)
 - Servicios Online (webs que ejecutan tu código y te muestra el resultado)
 - Usar JavaScript como lenguaje backend con Node.js

Yo lo haré con **Node.js**, pero os dejo en enlaces de interés un enlace para ver cómo ejecutar JavaScript en la terminal de nuestro navegador y también de una web para ejecutar JavaScript.

### No son apuntes de Node.js
Voy a dejar claro que, aunque recomiende usar Node.js para ejecutar nuestro código de JavaScript e ir haciendo pruebas, esto **no son apuntes de Node.js**

Simplemente os doy los pasos necesarios para ejecutar nuestro código en terminal con Node.js. Estos pasos son:

 - Instalar Node.js
 - Empezar proyecto en Node.js
 - Ejecutar archivo JavaScript en terminal con Node.js
 
 Para todo lo demás te recomiendo visitar el partado de ***Enlaces de interés*** donde os dejaré un recurso algo más completo de Node.js

## Instalación y uso básico de Node.js
Instalar Node.js es realmente sencillo. Tan solo tendremos que [irnos a su web](https://nodejs.org/es/download/), descargar el instalador, ejecutarlo y ya estará instalado en nuestro equipo.

Una vez que lo tengamos instalado, para utilizarlo lo podremos hacer con el terminal de comandos de nuestro equipo (CMD para Windows y el terminal para Linux y MacOS) o bien usar el terminal integrado en Visual Studio Code.

### Terminal de VSCode

Por sencillez y rapidez, os recomiendo el **terminal de VSCode**. Abriendo en la barra de herramientas "Terminal" > "Nuevo terminal" nos aparecerá ya abajo el terminal listo para ejecutar.

### Comenzar proyecto con Node.js
Para crear nuestro proyecto nos tendremos que dirigir a la carpeta raiz del proyecto usando el comando cd. Si has abierto ya tu carpeta raiz en VSCode, el terminal ya se encontrará en dicha carpeta.

Una vez que nos encontremos en la carpeta, para empezar un nuevo proyecto Node.js tan solo tendremos que ejecutar:

     npm init-y
Esto nos creará la estructura necesaria con un archivo package.json de configuración con la información del proyecto.
### Ejecutar archivo JavaScript con Node.js

Si queremos ejecutar un archivo JavaScript en Node.js y ver el resultado en la terminal, tan solo nos tendremos que ubicar en la carpeta donde se encuentra (de nuevo con cd) y escribir:

    node nombreDelarchivo.js
Con esto ya estaremos ejecutando nuestro código JavaScript en un terminal sin necesidad de usar un navegador, archivos HTML, etc.
## Comentarios y console.log
### Comentarios en JavaScript
Dentro de nuestros archivos y código de JavaScript vamos a poder ir introduciendo **comentarios para ir aclarando partes del código**. Comentar un código es una buena práctica (bueno, comentar demasiado un código es una mala práctica).

Las **dos formas más comunes** para comentar un código en JavaScript son:

 - Con comentario de una línea: //
 - Con comentarios de varias líneas:  /* */

### console.log
Durante estos apuntes y, programando en JavaScript de forma general, vamos a usar muy frecuentemente la función **console.log()**.

**console.log** lo que hará es mostrar por el terminal la información que le pasemos como parámetro, es decir, entre los paréntesis. Esta información puede ser un texto, una variable, un objeto... prácticamente cualquier cosa.

    //Ejemplo de un comentario de una línea
    
    console.log("Hola mundo")
    console.log(3)
    
    /* Ejemplo
    de un comentario
    de varias líneas */

    console.log(miVariable)
    console.log(typeof miObjeto)

Así que más te vale acostumbrarte a console.log(), pues aunque no quieras, lo harás.

## Enlaces de interés

 - [Qué es JavaScript, características](https://www.ecured.cu/JavaScript)
 - [Play Code, Editar y ejecutar JavaScript online](https://playcode.io/javascript-online)
 - [Ejecutar JavaScript en Google Chrome](https://www.delftstack.com/es/howto/javascript/run-a-javascript-file-in-chrome/)
 - [Iniciación a Node.js](https://www.youtube.com/watch?v=gnF3qWet3HA)
