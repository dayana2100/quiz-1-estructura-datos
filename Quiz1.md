Diferencia entre un IDE y un editor de texto
*IDE*
Es un programa más pesado que pide mucha más memoria RAM y un procesador más poderoso.
Contienen herramientas integradas, es decir, ahora ya no crearás carpetas por tu cuenta, pueden tener un compilador (para los lenguajes compilados)
Se especializa en un lenguaje (JAVA,PYTHON,GO,ANDROID)

Eclipse, IntelliJ IDEA, Android Studio y Visual Studio son los IDES más conocidos

*Editor de texto*
Es un programa ligero que no exige mucha RAM o procesador
Soporta múltiples lenguajes y tecnologías 
Se pueden agregar plugins para darle poder de un IDE pero se debe configurar cada uno a mano

Dentro de los editores más populares se encuentran Visual Studio Code, Sublime Text, Notepad++ y Vim.

2.*LENGUAJES TIPADOS*
Se caracterizan por que requieren que que definamos el tipo de dato específico de las variables y expresiones que vamos a utilizar.
Ejemplos de lenguajes tipados son C++ y Java, entre otros muchos.
en un lenguaje tipado tenemos que indicar el tipo de variable al declararla, por ejemplo un número entero int o una cadena de texto string.
Una vez que una variable tenga un tipo esta solo puede contener valores compatibles con este tipo. No podríamos asignar a una variable int un texto.
*LENGUAJES NO TIPADOS*
No necesitan que indiquemos el tipo de las variables y expresiones al declarar la variable.Ejemplos de lenguajes no tipados son Python y JavaScript. 
En la gran mayoría de lenguajes no tipados es posible incluso cambiar el tipo de variable una vez creada.
En realidad, internamente los lenguajes no tipados si tienen tipos. Tu programa lo necesita para saber como manipular los valores de las variables. Pero el lenguaje de programación hace que su uso sea transparente para el usuario la mayoría de las veces.

*TIPO DE DATOS EN JAVA*
Datos primitivos
Los datos primitivos son tipos de datos básicos que representan valores simples y se almacenan directamente en la memoria.
Algunos ejemplos de datos primitivos en Java incluyen int para números enteros, double para números decimales y boolean para valores lógicos verdaderos o falsos, entre otros.
La lista de datos primitivos pueden ser:
•byte: Representa un tipo de dato de 8 bits con signo. Puede almacenar valores numéricos en el rango de -128 a 127, incluyendo ambos extremos. Es útil para ahorrar memoria cuando se necesita almacenar valores pequeños.
•short: Este tipo de dato utiliza 16 bits con signo y puede almacenar valores numéricos en el rango de -32,768 a 32,767. Se utiliza cuando se necesita un rango más amplio que el proporcionado por los bytes, pero aún se desea ahorrar memoria en comparación con los tipos de dato más grandes.
•int: Es un tipo de dato de 32 bits con signo utilizado para almacenar valores numéricos. Su rango va desde -2,147,483,648 (-2^31) hasta 2,147,483,647 (2^31 - 1). Es el tipo de dato más comúnmente utilizado para representar números enteros.
•long: Este tipo de dato utiliza 64 bits con signo y puede almacenar valores numéricos en el rango de -9,223,372,036,854,775,808 (-2^63) a 9,223,372,036,854,775,807 (2^63 - 1). Se utiliza cuando se necesitan números enteros muy grandes.
•float: Es un tipo de dato diseñado para almacenar números en coma flotante con precisión simple de 32 bits. Se utiliza cuando se requieren números decimales con un grado de precisión adecuado para muchas aplicaciones.
•double: Este tipo de dato almacena números en coma flotante con doble precisión de 64 bits, lo que proporciona una mayor precisión que float. Se usa en aplicaciones que requieren una alta precisión en cálculos numéricos.
•boolean: Sirve para definir tipos de datos booleanos que pueden tener solo dos valores: true o false. Aunque ocupa solo 1 bit de información, generalmente se almacena en un byte completo por razones de eficiencia.
•char: Es un tipo de datos que representa un carácter Unicode sencillo de 16 bits. Se utiliza para almacenar caracteres individuales, como letras o símbolos en diferentes lenguajes y conjuntos de caracteres.
*Datos de referencia*
Los datos de referencia son tipos de datos más complejos que hacen referencia a objetos almacenados en memoria. Estos objetos pueden ser instancias de clases personalizadas o clases predefinidas en Java, como String.
Los datos de referencia no almacenan directamente el valor, sino una referencia a la ubicación en memoria donde se encuentra el objeto.
Datos de referencia especiales
Java también tiene tipos de datos de referencia especiales, como null, que representa la ausencia de un objeto, y void, que se utiliza en métodos que no devuelven ningún valor.
