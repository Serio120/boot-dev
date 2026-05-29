# Literales de plantilla

En JavaScript, los [literales de plantilla](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals) son una forma fantástica de interpolar valores dinámicos en una cadena. Son la versión de JavaScript de las cadenas f de Python. Por ejemplo:

```javascript
const shadeOfRed = 101;
console.log(`The shade is ${shadeOfRed}`);
// The shade is 101
```
Los literales plantilla deben comenzar y terminar con un backtick, y cualquier cosa dentro del recinto del corchete de signo de dólar se convierte automáticamente en una cadena.

## Lógica avanzada
No estás limitado solo a nombres de variables dentro del archivo . De hecho, puedes escribir código JavaScript válido directamente dentro de ellos.${}

Esto significa que puedes hacer matemáticas, cambiar estilos de texto o hacer comprobaciones lógicas justo dentro de la cadena.

```javascript
const price = 2.5;
const quantity = 3;
const item = "coffee";

console.log(`Total: $${price * quantity}`);
// Total: $7.5

console.log(`I need ${item.toUpperCase()}`);
// I need COFFEE
```

## Asignación
Usando los literales de la plantilla y el formato de cadenas ilustrados arriba, crea una nueva variable y asigna la cadena:msg

Hi NAME, your open rate is OPENRATE percent

Sustituye por la variable .NAMEname
Sustituye por la variable .OPENRATEopenRate

## Solución

```javascript
const name = "Saul Goodman";
const openRate = 30.5;

const msg = `Hi ${name}, your open rate is ${openRate} percent`;

// don't touch below this line
console.log(msg);
```
