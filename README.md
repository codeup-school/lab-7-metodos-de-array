# 🧪 Lab: Métodos de Arrays en JavaScript

## Instrucciones

Completa los siguientes ejercicios para practicar los métodos de arrays que hemos aprendido: `.map()`, `.forEach()`, `.filter()`, `.reduce()`, `.sort()`, y `.reverse()`. Intenta resolver cada uno antes de mirar las soluciones al final.

### 1. Usando `.map()`

Tienes el siguiente array de números. Usa el método `.map()` para crear un nuevo array que contenga cada número multiplicado por 10.

```javascript
const numbers = [1, 2, 3, 4, 5];
// Escribe tu código aquí
```

### 2. Usando `.forEach()`

Dado el siguiente array de nombres, usa el método `.forEach()` para imprimir cada nombre en la consola con un saludo.

```javascript
const nombres = ["Ana", "Juan", "Pedro", "Lucía"];
// Escribe tu código aquí
```

### 3. Usando `.filter()`

Tienes un array de edades. Usa el método `.filter()` para crear un nuevo array que contenga solo las edades mayores o iguales a 18.

```javascript
const edades = [12, 17, 22, 8, 34, 15];
// Escribe tu código aquí
```

### 4. Usando `.reduce()`

Dado un array de precios, usa el método `.reduce()` para calcular el precio total.

```javascript
const precios = [10.99, 5.99, 20, 3.5];
// Escribe tu código aquí
```

### 5. Usando `.sort()`

Tienes el siguiente array de números. Usa el método `.sort()` para ordenarlo de menor a mayor.

```javascript
const numeros = [5, 1, 8, 3, 7];
// Escribe tu código aquí
```

### 6. Usando `.reverse()`

Dado el siguiente array de letras, usa el método `.reverse()` para invertir el orden de los elementos.

```javascript
const letras = ["a", "b", "c", "d", "e"];
// Escribe tu código aquí
```

---

## Soluciones

### 1. Usando `.map()`

Multiplica cada número del array por 10:

```javascript
const numbers = [1, 2, 3, 4, 5];
const multiplicados = numbers.map((num) => num * 10);
console.log(multiplicados); // [10, 20, 30, 40, 50]
```

### 2. Usando `.forEach()`

Imprime un saludo para cada nombre:

```javascript
const nombres = ["Ana", "Juan", "Pedro", "Lucía"];
nombres.forEach((nombre) => {
  console.log(`Hola, ${nombre}!`);
});
// Resultado en consola:
// Hola, Ana!
// Hola, Juan!
// Hola, Pedro!
// Hola, Lucía!
```

### 3. Usando `.filter()`

Filtra las edades mayores o iguales a 18:

```javascript
const edades = [12, 17, 22, 8, 34, 15];
const mayores = edades.filter((edad) => edad >= 18);
console.log(mayores); // [22, 34]
```

### 4. Usando `.reduce()`

Calcula el total de los precios:

```javascript
const precios = [10.99, 5.99, 20, 3.5];
const total = precios.reduce((acumulador, precio) => acumulador + precio, 0);
console.log(total); // 40.48
```

### 5. Usando `.sort()`

Ordena los números de menor a mayor:

```javascript
const numeros = [5, 1, 8, 3, 7];
numeros.sort((a, b) => a - b);
console.log(numeros); // [1, 3, 5, 7, 8]
```

### 6. Usando `.reverse()`

Invierte el orden de las letras:

```javascript
const letras = ["a", "b", "c", "d", "e"];
letras.reverse();
console.log(letras); // ['e', 'd', 'c', 'b', 'a']
```
