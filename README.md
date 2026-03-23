# README.md

## Probando comandos en GIT.

##### Este archivo es para probar comandos desde la consola. Actualmente no tenemos este archivo readme en el repositorio. Lo agregaremos con el comando **add**.README.md desde la terminal. Este será nuestro primer **commit**.

## Ejercicio Hello World

###   <img src="img/js.png" width="30" style="vertical-align: -5px">
````javascript
console.log("Hola mundo");
````

### <img src="img/py.png" width="30" style="vertical-align: -5px">
````python
print("Hola Mundo")
````

### <img src="img/a.png" width="30" style="vertical-align: -5px">
````c#
using System;

class Program{
    static void Main(string[] args){
        Console.WriteLine("Hola Mundo");
    }
}
````

---


## Ejercicio Hello World con <span style="color: rgba(350, 120, 700);">`funciones`</span>.

###  <img src="img/js.png" width="30" style="vertical-align: -5px">

````javascript
function saludar(nombre) {
    console.log('Hola, ' + nombre);
}
saludar("Mundo");
````

###  <img src="img/py.png" width="30" style="vertical-align: -5px">

````python
def saludar(nombre) {
    print("Hola, " + nombre)
}
saludar("Mundo")
````

###  <img src="img/a.png" width="30" style="vertical-align: -5px">

````c#
using System;
class Program
{
    static void Saludar(string nombre)
    {
        Console.WriteLine("Hola, " + nombre)
    }

    static void Main(string[] args)
    {
        Saludar("Mundo");
    }
}
````

## Ejercicio HelloWorld con arrow functions.

###   <img src="img/js.png" width="30" style="vertical-align: -5px">

````javascript
const holaMundo = () => {
  console.log("Hola mundo");
};

holaMundo();

/*O también*/

const holaMundo = () => console.log("Hola mundo");

holaMundo();

````
### como hacer un pull request


### Ejercicio HelloWorld con Bash

````bash
echo "Hello World"
````