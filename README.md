# Jascript
- Lenguage interpretado: ya que el navegador lee línea por línea el código
- Orientado a objetos: utiliza objetos
- Débilmente tipado: permite operaciones entre diferentes tipos de datos
- Dinámico: que se ejecuta directamente y no necesita compilarse

## Historia
Javascript nace por la necesidad de darle dinamismo a las páginas y que los usuarios puedan interactuar con el contenido o generar el suyo.

## Conceptos

### Forwads
Es compatibles con versiones futuras

### Backwards
No es compatible con versiones futuras, pero el código seguirá funcionando como Javascript, se puede solucionar con compiladores como BabelJS

### Función declarativa
`function mifuncion() { }`

### Función de exprecion o anónimas
`var mifuncion = function() { }`

### Scope
Es el alcance que tienen las variables
- **Scope Global:** se genera cuando nuestro archivo js se iniciliza en el navegador.
- **Scope Local:** se genera cuando comenzamos una función.

### Hoisting
Cuando las variables y las funciones se declaran antes que se procese cualquier tipo de código.

### Coerción
Cambiar un tipo de valor a otro tipo de valor
- **Coerción Implícita:** cuando el lenguage nos ayuda 4 + "7"
- **Coerción Explícita:** cuando obligamos al cambio String(), Number()

### Métodos de Array
- **map:** regresa un array con las coordinaciones o adiciones
- **filter:** regresa un array filtrado
- **find:** regresa el objecto buscado o undefined
- **forEach:** recorre un array
- **some:** regresa true o false

- **push:** agrega un elemento al final del array
- **pop:** elimina el último elemento del array
- **shift:** elimina el primer elemento del array
- **unshift:** agrega un elemento al inicio del array