
## 2.1. Variables

En programación es muy recurrente el uso de variables para almacenar, manipular y mostrar información. Es por ello que vamos a empezar por ellas, vamos a ver **qué es una variable, cómo se declara y cómo se pueden utilizar**.
### Qué es una variable
En programación, una **variable es un nombre que hace referencia a un espacio en la memoria del programa** donde se guarda un dato. Básicamente una variable está formada por un espacio en la memoria y un nombre simbólico que hace referencia a dicho espacio. Vamos a usar el nombre simbólico para hacer referencia al valor almacenado y así poder obtenerlo, manipularlo, mostrarlo...

De forma resumida podemos decir que con el u**so de variables vamos a almacenar datos bajo un nombre** y que, para hacer uso de esos datos, tan solo nos tenemos que servir del uso del nombre. Quizás con un ejemplo es más claro:

    //Almaceno en la variable "miNumeroUno" el valor 3
    let miNumeroUno = 3
    //Almaceno en la variable "miNumeroDos" el valor 2
    let miNumeroDos = 2
    //Almaceno en la variable "resultado" el resultado de la suma
    let resultado = miNumeroUno + miNumeroDos

   No hace falta que entiendas ya por qué se declaran de esta forma las variables en JavaScript, porque lo vamos a ver un poco más abajo. Simplemente tienes que entender que los identificadores de la variable (sus nombres) van a hacer referencia al valor que le hemos asignado. Así pues la variable "resultado" tendrá como valor el resultado de la operación de 3+2, es decir, 5.
   


   **A retener de este apartado:**
   

 - *Una variable es un identificador (nombre) que hace referencia a un valor guardado en un espacio de la memoria.*
 - *Para usar, modicar o mostrar ese valor tan solo tendremos que usar el identificador.*

 
 
### Declaración e inicialización de una variable
Para utilizar las variables en cualquier lenguaje de programación tenemos que tener claro dos conceptos: la **declaración** y la **iniciación** de una variable.
 - Estamos **declarando una variable** cuando estamos asignando a un espacio de memoria vacio un nombre. No le estamos asignando todavía el valor que va a almacenar.
 - Estamos **inicializando una variable** cuando le asignamos un valor a una variable ya declarada.

Veámoslo con un ejemplo:

    //Declaración de una variable
    let miVariable
    //Inicialización de una variable
    miVariable = 3
Como véis, hemos declarado una variable por un lado y luego le hemos asignado un valor. Tanto en JavaScript como en demás lenguajes, esto lo podemos hacer en un única línea, ahorrándonos tiempo:

    //Declaración e inicialización de una variable
    let miVariable = 3

Esta última forma es la más común, pero está bien que sepas que se puede hacer por separado, ya que también se suele declarar una variable al principio del programa para asignarle un valor más adelante.

### Declaración de una variable en JavaScript (var, let y const)
Como habéis podido observar, para declarar una variable he usado la **palabra reservada let**.

Una **palabra reservada es** una palabra que no podemos usar como queramos en el lenguaje de programación porque ya tiene una función predefinida. En JavaScript tenemos 3 palabras reservadas para declarar variables: **var, let y const**. Estas palabras solo la podremos usar para declarar variables.

Así pues, **para declarar una variable** tendremos que escribir una de estas palabras reservadas seguida de su nombre:

    var miVariableConVar
    let miVariableConLet
    
    //Con const tenemos que declarar e inicializar
    //de forma obligatoria al mismo tiempo
    const miVariableConConst = 1

Aunque las tres formas sirven para declarar una variable, hay **diferencias entre ellas**. 

Básicamente **var y let** tienen la misma funcionalidad: declarar una variable que su valor puede ir cambiando durante la ejecución del programa. Aunque var y let tienen la misma función, desde ES6 se recomienda utilizar let para declarar una variable, así que utilizar var hoy en día es una mala práctica por el tema de el ámbito de ambas. Os dejo en los enlaces de interés un artículo sobre esto.

Luego tenemos **const**, const sirve para declarar una variable que tiene un varlo que no puede cambiar durante la ejecución del programa. Por eso se llama const, porque es CONSTANTE. Además, cuando declaramos una constante, tenemos que declarar e inicializarla en la misma línea.

   **A retener de este apartado:**
   

 - *Var, let y const son palabras reservadas que solo podemos utilizar para declarar variables o constantes*
 - *Var y let tienen la misma función: declarar una variable. Pero usaremos let en lugar de var.*
 - *Const sirve para declarar e inicializar una constante, debemos hacerlo al mismo tiempo.*

### Enlaces de interés
 - [Var, let y const, cuál es la diferencia](https://www.freecodecamp.org/espanol/news/var-let-y-const-cual-es-la-diferencia/)

