---
title: C#
image: "/assests/images/csharp.svg"
---

## Índice 

-[Índice](#índice)
-[Introducción a C#](#introducción)
    -[¿Qué es C#?](#qué-es-c)
    -[¿Para que se utiliza C#?](#para-qué-se-utiliza-c)
-[Variables en C#](#variables-en-c)
    -[Tipos de datos](#tipos-de-datos)
    -[Declaración de variables](#declaración-de-variables)
        -[var](#var)
        -[const](#const)


<br>

## Introducción

### ¿Qué es C#?

C# es un lenguaje de programación, orientado a objetos, el cual es comunmente utilizado en la plataforma .NET. La sintaxis de C# es muy similar al de C++ y Java. 

### ¿Para qué se utiliza C#? 

C#, en general, se suele utilizar para hacer diversos tipos de proyectos, como por ejemplo, aplicaciones de escritorio, desarrollo web en el entorno ASP.NET, desarrollo de videojuegos en motores como Unity, entre otros. 

## Variables en C# 

### Tipos de datos
C# es un lenguaje tipado, esto significa que **debemos** indicar el tipo de dato tendrá esta variable. Por ejemplo:

```csharp
int numero = 10; // Numeros enteros
float numero2 = 1.5; // Numeros con decimales 
string alumno = "Juan"; // Cadena de caracteres
string alumno2 = $"{alumno} Pérez"; // Concatenación que acepte variables
bool aprobado = true; // Booleanos
char letra = "A"; // Único caractér
``` 

Sin embargo, podemos encontrar aún más tipos de datos en C#.

### Declaración de variables
En C#, además de poder declarar las variables simplemente indicando su tipo de dato, tenemos otras dos maneras de poder hacerlo. 

#### var

```csharp
var nombre = "Joaquín"; 
var numero = 5; 
var realizado = false; 
```

Esta forma de declarar variables con `var` nos permite omitir el tipo de dato, ya que se infiere el mismo a la hora de asignarle un valor. Luego de inicializarla, se puede cambiar dicho valor, pero **no** su **tipo** de dato. 

#### const 

```csharp
const apellido = "González"; 
const dni = 12345678; 
const tramitado = true; 
```

Por otro lado, si utilizamos `const`, estamos declarando variables que serán **constantes**, y que se mantendrán con dicho valor inicial. Esto nos podría llegar a servir para evitar asignaciones no deseadas con ciertas variables. 