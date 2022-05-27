# JavaScript
_Notes for javascript_

La comilla invertida nos ayuda a imprimir variables y escribir codigo directamente:
```
`${variable} ${variable.metodo()}`
```
Cuando algo no tiene un valor especifico es undefined.
Variables fuera de funciones, son de ámbito global. En un navegaoor la variable global se encuentra en el objeto window (window.variable)
Puede haber 2 variables en el ámbito globar y en el local de una función con el mismo nombre.

Devuelve el tipo de valor que tiene:
```
typeof(variable)
```
Devuelve su correspondiente valor a boolean para mayor claridad en comparaciones:
```
Boolean(variable)
Boolean(string 1 o mas caracteres) //true
Boolean(string vacio) //false
Boolean(numeros != de 0) //true
Boolean(numeros = a 0) //false
Boolean(undefined) //false
Boolean(null) //false
Boolean(Object vacio o con alguna propiedad) //true
```
NaN (Not a Number):
```
isNan(NaN) // true
isNan(10) // false
isNan("10") // false
isNan("azul") // true
isNan(true) // false
NaN == NaN //false
NaN/10 // NaN  cualquier operacion con NaN devuelve NaN
```
Number
```
Number(true) // 1
Number(10) // 10
Number(null) // 0
Number(undefined) // NaN
Number("123") // 123
Number("1.2") // 1.2
Number("") // 0
Number("hola") // NaN
```
parseInt
```
parseInt("2.5") // 2
parseInt("10") // 10
parseInt("0011") // 11
parseInt("123Azul") // 123
parseInt("Azul123") // NaN
parseInt("") // NaN
```
parseFloat
```
parseFloat("123Azul") // 123
parseFloat("11.5") // 11.5
parseFloat("22.4.36.56") // 22.4
parseFloat("12.3Azul") // 12.3
parseFloat("Azul123") // NaN
parseFloat("098.4") // 98.4
```
Para agregar una propiedad a un objeto:
```
obj.nueva = "val" 
> { name: "nombre", nueva: "val" }
```
Para borrar una propiedad de un Obj
```
delete obj.nueva 
> { name: "nombre"}
```
Equivalentes para acceder a una propiedad de un objeto
```
obj.propiedad
obj['propiedad']
```

Creacion de una clase en JS
```
function Clase() { atributos, metodos }
var clase = new Clase()
```

Editor online JSON: https://jsoneditoronline.org/
