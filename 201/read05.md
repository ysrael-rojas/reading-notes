# READ 05: ESTRUCTURAS DE CONTROL Y DATOS EN JAVASCRIPT

## 1. Cuáles son los diferentes tipos de estructuras condicionales en JavaScript y en qué situaciones deberías usar cada una? explicame de manera sencilla❓

- ```if```: Se usa cuando quiero ejecutar codigo solo si se cumple una condicion.
- ```else if```: Cuando necesito hacer o bien una cosa o bien otra, dependiendo de la condicion.
- ```if...else if...else```: cuando hay multiples condiciones.
- ```operador ternario```: Es como un ***if else*** mas corto, util para asignaciones simples.
- ```switch```: Cuando necesitas comparar una variable contra varios valores posibles.

## 2. En el contexto de arreglos en JavaScript, ¿cuál es la diferencia entre los métodos push(), unshift() y splice(), y cuándo usarías cada uno❓

- ***push()***: Añade elementos al final de un arreglo.

```javascript
let frutas = ['manzana', 'pera'];
frutas.push('naranja');
// Resultado: ['manzana', 'pera', 'naranja']
```

- ***unshift()***: Añade elementos al inicio de un arreglo.

```javascript
let frutas = ['manzana', 'pera'];
frutas.unshift('naranja');
// Resultado: ['naranja', 'manzana', 'pera']
```

- ***splice()***: Es más flexible, permite agregar o eliminar elementos en cualquier posición. También podemos reemplazar elementos existentes.

```javascript
let frutas = ['manzana', 'pera', 'naranja'];
// Eliminar 'pera' e insertar 'uva' y 'kiwi' en su lugar
frutas.splice(1, 1, 'uva', 'kiwi');
// Resultado: ['manzana', 'uva', 'kiwi', 'naranja']
```

## 3. Qué diferencias existen entre los bucles for, while y do...while❓ Proporciona un ejemplo práctico de uso para cada uno

- ***for***: Se usa cuando sabemos cuantas veces vamos a repetir algo.

```javascript
// Ejemplo: Contar del 1 al 5
for (let i = 1; i <= 5; i++) {
    console.log(i);
}
```

- ***while***: Se usa cuando no sabemos exactamente cuántas iteraciones necesitaremos.

```javascript
/// Ejemplo: Generar números aleatorios hasta obtener uno mayor a 0.8
let numero = 0;
while (numero <= 0.8) {
    numero = Math.random();
    console.log(numero);
}
```

- ***do while***: Similar al while, pero garantiza que el código se ejecute al menos una vez. La condición se verifica después de ejecutar el código.

```javascript
/// Ejemplo: Generar números aleatorios hasta obtener uno mayor a 0.8
// Ejemplo: Menú de opciones
let opcion;
do {
    opcion = prompt(`
        1. Ver perfil
        2. Editar perfil
        3. Salir
        Elige una opción:`);
} while (opcion !== '3');
```

## 4. Cómo se puede recorrer un arreglo en JavaScript utilizando diferentes tipos de bucles y cuál consideras más eficiente según el caso de uso❓

