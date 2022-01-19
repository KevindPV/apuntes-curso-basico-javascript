<!-- IMAGEN DE INICIO -->
<a name="inicio"></a>

![Javascript logo](javascript-logo.png)
<!-- CONTENIDO CURSO -->


# CONTENIDO DEL CURSO
## [Modulo 1 Introducción a JavaScript](#modulo1)

* [**Clase 1**](#clase1)   ¿Qué es JavaScript?
* [**Clase 2**](#clase2) ¿Por qué JavaScript?
* [**Clase 3**](#clase3) Elementos de un Lenguaje de Programación: Variables, Funciones y Sintaxis
* [**Clase 4**](#clase4) Variables en JavaScript 
* [**Clase 5**](#clase5) Funciones en JavaScript
* [**Clase 6**](#clase6) Funciones en JavaScript
* [**Clase 7**](#clase7) ¿Qué es una función declarativa y una expresiva?  
  

## Modulo 2 Bases de JavaScript

* [**Clase 8**](#clase8) Scope
* [**Clase 9**](#clase9) Hoisting
* [**Clase 10**](#clase10) Coerción
* [**Clase 11**](#clase11) Valores: Truthy y Falsy
* [**Clase 12**](#clase12) Operadores: Asignación, Comparación y Aritméticos.

## Modulo 3 Condicionales

* [**Clase 13**](#clase13) Condicionales: If, Else, else if
* [**Clase 14**](#clase14) Switch
  

## Modulo 4 Arrays

* [**Clase 15**](#clase15) Arrays

  
## Modulo 6 Loops
 
* [**Clase 16**](#clase16) Loops: For y For...of
* [**Clase 17**](#clase17) Loops: While


## Modulo 7 Objects

 
* [**Clase 18**](#clase18) Objects
* [**Clase 19**](#clase19) Objects: Función constructora

 
## Modulo 8 Métodos de Arrays

* [**Clase 20**](#clase20) Métodos de recorridos de Arrays
* [**Clase 21**](#clase21) Recorriendo Arrays con .find(), .forEach() y .some()
* [**Clase 22**](#clase22) Eliminando elementos de un Array 


## Modulo 9 Próximos pasos con JavaScript
 
* [**Clase 23**](#clase23) Continúa con el Curso Práctico de JavaScript

<a name="modulo1"></a>

# **<span style="color:red"> Modulo 1 Introducción a JavaScript </span>** 

[**Volver al inicio**](#inicio)
<a name="clase1"></a>
## **<span style="color:yellow"> **Clase 1** ¿Qué es JavaScript? </span>** 

### **¿Cómo nace JavaScript?**

Nace con la necesidad de generar dinamismo en las páginas web y que a su vez los usuarios y las empresas pudieran interactuar unos con otros.

### **¿Qué es JavaScript?**

Es un lenguaje **<span style="color:red"> interpretado </span>**, orientado a objetos, débilmente tipado y dinámico.

**Débilmente tipado** 
Se pueden hacer operaciones entre tipos distintos de datos (enteros con strings, booleanos con enteros, etc.).

``` javascript
4 + "7"; // 47
4 * "7"; // 28
2 + true; // 3
false - 3; // -3
```
**Dinámico**
Corre directamente en la etapa de Runetime sin una etapa de compilación previa. Esto permite probar nuestro código inmediatamente; pero también es lo que hace que los errores se muestren hasta que se ejecuta el programa.

### **¿Realmente es JavaScript un lenguaje interpretado?**

Si, y la razón es que el navegador lee linea por linea nuestro código el cuál le indica lo que tiene que hacer, sin la necesidad de compilar. Todo esto es controlado por el motor de Javascript V8 del navegador

[**Volver al inicio**](#inicio)
<a name="clase2"></a>
## **<span style="color:yellow"> **Clase 2** ¿Por qué JavaScript? </span>** 

JavaScript tiene una comunidad enorme de desarrolladores que te pueden ir ayudando a generar diferentes cosas.

1. Si solo estuvieras interesado en trabajar aplicaciones web tienes muchos frameworks y librerías construidas en JavaScript que te van a ayudar a hacer proyectos de forma mucho mas rápida, eficiente y robusta (Angular, View, React,entre otros)

2. Si no quieres trabajar solo en aplicaciones Web puedes utilizar JavaScript con un framework que se llama React Native para poder construir aplicaciones nativas como Android y IOS.
3. Puedes construir aplicaciones de escritorio con JavaScript, usando un framework llamado Electron, pueden correr en Mac o Windows.
4. También puedes trabajar en la parte del Back-end o **IOT**(Internet Od Things) es un concepto que se refiere a una interconexion digital de objetos cotidianos con Internet. Esto con un Framework llamado NodeJS, el cual es un entorno de ejecución de JavaScript que corre directamente en el Back-end.

![node js logo](nodejslogo.jpg)

[**Volver al inicio**](#inicio)
<a name="clase3"></a>
## **Clase 3** ¿Por qué JavaScript? 

 Hay dos componentes principales:
 1. Data que guardamos en memoria
 2. Tareas(funciones) que haremos con esa data

existen estos tipos de datos:

``` javascript
// Tipos primitivos

40 // numeros

// strings
"Diego de granda"

// booleanos
truefalse

//valores vacios
null
undefined

// tipos de objetos o no primitivos

[1,2,3] // corchetes // arrays
{ nombre: "Kevin"} // llaves / objetos

```

### ¿Como comprobar que esta informacion? 