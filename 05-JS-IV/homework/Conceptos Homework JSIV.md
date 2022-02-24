Conceptos Homework JSIV

1 - En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.

Objetos: Un objeto es una coleccion de informacion sobre una misma cosa. La informacion dentro del objeto se organiza en lo que se llama "propiedades". A diferencia de los arreglos que contenian información indizada (con un orden establecido) [1] [2] [3], los objetos contienen que puede estar desordenada y cada dato hace referencia a un nombre, no a un número. Se puede decir que los arrays son un tipo de objeto en el cual la informacion tiene un orden y cada dato se puede invocar haciendo referencia a ese número que oficia de indice. En el caso de los objetos, la informacion se invoca haciendo referencia al nombre del dato, que no tiene un orden prestablecido. Resumiendo, los objetos son un conjunto de propiedades que hacen referencia a una misma cosa, estas propiedades pueden ser cualquier tipo de dato y se denotan como una combinacion clave (nombre): valor. 

Propiedades: Las propiedades son el nombre que se le da a los diferentes tipos de datos que hacen a la información de un objeto. Cada propiedad hace referencia a una característica diferente del objeto y es una asociación entre un nombre (de la propiedad) o clave y un valor. Una propiedad de un objeto puede ser cualquier tipo de dato que haga referencia a el, un 'string', un número, un booleano, una variable, un arreglo, una funcion u otro objeto.
Se puede invocar a una propiedad de un valor haciendo referencia al al objeto y la propiedad que queremos invocar. Esta invocación se puede hacer de dos maneras, la primera, "braket notation", se da escribiendo el nombre del objeto, espacio y el nombre de la porpiedad entre corchetes. La segunda notacion, denominada "DOT notation", se da escribiendo el nombre del objeto, punto, y el nombre de la propiedad.

Métodos: Se denomina "método de un objeto" a aquellas funciones que forman parte de las propiedades del mismo. Es decir, puede que algunas propiedades del objeto sean funciones, estas funciones, se denominan métodos.

Bucle for…in: El bucle for...in es un tipo de bucle for, integrado, que se puede utilizar para iterar sobre todas las clave:valor del objeto. Para las matrices o arrays, se utilizo hasta ahora el bucle for standar, que toma como variable el numero indice del array:  
for (var = i;  ......)
En cambio, para los objetos, utilizamos el bucle for...in, que toma como variable la clave y busca "in", dentro del objeto, devolviendo el valor asociado a esa clave:
for (var clave in "objeto") {
	console.log(clave);
	console.log(objeto[clave]);
}
devolvera algo como lo siguiente:
// clave1
// dato1
// clave2
// dato2...
... asi sucesivamente hasta recorrer todo el objeto.

Notación de puntos vs notación de corchetes: Para invocar las propiedades de los objetos, se puede utilizar la "braket notation" o notación de corchetes, que se utiliza de la siguiente forma:
objeto[nombreDeLaPropiedad];
También se puede utilizar la "DOT notatión" o notación de puntos, que se utiliza de la siguiente manera:
objeto.nombreDeLaPropiedad;
La notación de puntos tiene la ventaja de ser mas facil de escribir, aunque es literal, es decir, solo puede recibir despues del punto, el nombre se una variable declarada con anterioridad dentro del objeto. La notacion de corchetes, en cambio, si bien es mas dificil de escribir, permite introducir entre corchetes por ejemplo, una variable que haga referencia a una propiedad y no solo el nombre de la propiedad.