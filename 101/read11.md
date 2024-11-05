# READ11: INTRODUCCION AL DOM Y PROYECTOS

## 1. Qué es el ***DOM***❓

El ```DOM``` es una representación en forma de estructura de árbol de todos los elementos HTML de una página, y JavaScript te permite modificar ese "árbol" dinámicamente.

## 2. Describe brevemente la relación entre el ***DOM*** y ***JavaScript***.

El ```DOM``` y ```JavaScript``` están estrechamente relacionados porque el ```DOM``` es la estructura que representa los elementos de una página web, y ```JavaScript``` es el lenguaje que te permite interactuar con esa estructura.

## 3. ¿Qué método usarías para seleccionar un elemento del ***DOM*** por su **ID** y cómo se utiliza❓

Para seleccionar un elemento del ```DOM``` por su ```ID```, se utiliza el método ```getElementById()```.

Este método recibe como argumento el ```ID``` del elemento que deseas seleccionar y devuelve el elemento correspondiente. Si no se encuentra ningún elemento con ese ```ID```, devuelve ```null```.

```js
// Seleccionamos un elemento con el ID 'miBoton'
var boton = document.getElementById('miBoton');

// Ahora puedes interactuar con el elemento, por ejemplo, cambiar su texto
boton.innerText = '¡Haz clic aquí!';
```

## 4. Qué método utilizarías para cambiar el color de fondo de un elemento en el ***DOM*** y cómo se implementaría❓

Para cambiar el color de fondo de un elemento en el ```DOM```, puedes utilizar la propiedad style del elemento y luego modificar su propiedad ```backgroundColor```.

```js
// Seleccionamos el elemento con el ID 'miElemento'
var elemento = document.getElementById('miElemento');

// Cambiamos el color de fondo
elemento.style.backgroundColor = 'green';
```

🏠 [***Regresar***](../README.md)
