# Intermedio

Ahora que hemos visto lo básico, podemos continuar con sintaxis más avanzada y nuevas cosas que antes no se habían visto. 

## Tables (Tablas)

Para crear tablas usamos el símbolo "|" como separador de columnas, y el símbolo "-" como separador de la cabezera de la tabla y las filas restantes. No es necesario que los símbolos se ubiquen uno debajo del otro, o que haya la misma cantidad.

| Syntax      | Description |
| --------- | --------- |
| Header      | Title     |
| Paragraph     | Text     |

Puedes añadir todo tipo de elementos dentro de tablas con exepción de bloques de código.

## Alignment (Alineación)

Se pueden alinear los textos dentro de las columnas de una tabla, colocando dos punto ":" al inicio, al final o en ambos lados de las líneas separadoras de la cabezera con los elementos, de esta manera. 

| Izquierda   | Centro      |  Derecha   |
| :---        |    :----:   |       ---: |
| Left        | Center      | Right      |

## Fence Code Blocks (Bloque de Código Cercado)

Hay otra forma de crear bloques de código, si no deseas usar la identación. Estos bloques deben usar tres acentos simples "`" y luego inmediatamente puedes colcoar un bloque.

```
a = 23
b = 34
print(a+b)
```

Otro dato muy importante es que puedes colocar el código coloreado o resaltado como si trabajaras en un entorno de desarrollo de código, esto puede usarse para casi todos los lenguajes, solo debes identificar el lenguaje luego de los primeros tres acentos.

```py
a = 2
b = 5
print("La suma de elementos es: ", a+b)
```
## Footnotes (Pies de Página)

Los Footnotes son un tipo de referencia que puede colocarse en cualquier parte de un documento, para realizarlos debemos colocar entre corchetes "[ ]", el símbolo "^" y luego un número o palabra clave. Más adelante se puede colocar la definición del Footnote, colocando el mismo símbolo y luego su descripción.

Aquí hay un Footnote simple [^1], y aquí hay uno más complejo. [^bignote]

## Definition Lists (Listas de Definición)

También es posible crear Listas de Definición que sirven cuando deseas describir el significado de ciertos elementos, se coloca primero el término a definir y en líneas abajao sus definiciones que deben empezar con dos puntos ":".

**First Term**
: Una definición del primer término

**Second Term**
: Una definición del segundo término.
: Otra definición del segundo término.

## Tasks Lists (Listas de Tareas)

Tambíen es posible crear Listas de Tareas, para esto se debe crear una Lista Desordenada y al inicio de los elementos se coloca corchetes "[ ]", si dentro se coloca una "x", significa que la tarea está hecha; y si no, entonces aún no se realiza.

- [x] Tarea número 1
- [x] Tarea número 2
- [ ] Tarea número 3


## Emojis :smirk_cat: 

Sí, se pueden colocar emojis 🎊, puedes copiarlos desde alguna otra aplicación, insertarlos desde Windows 😊. Pero también puedes codificarlos usando el shortocode para Markdown; para esto colocas dos puntos y dentro el nombre clave del emoji :smile:.


[^1]: Un primer Footnote.

[^bignote]: Un footnote más ==complejo== con código incluido.
    
    Se debe identar con un Tab para indicar que esto es parte del Footnote.  
    `codigo`  

## StrikeThrough (Tachado)

para realziar un Tachado de texto debes colocar dos simbolos de virguilla "~" al inicio y al final de lo que deseas tachar.

~~Texto Tachado con dos Virguillas~~
