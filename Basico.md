# Básico

Markdown es un Lenguaje de Escritura Ligera que sirve para crear documentos de texto, compatible con HTML y además es bastante usado por muchos dentro del mundo de la programación. Por esto veremos aquí la sintaxis básica para realizar este tipo de docs.

[Comentarios con dos corchetes, dos puntos y un "#"]: #

## Headings (Encabezados)

Los encabezados son estos títulos grandes que van en la parte superior de párrafos por lo general. Se colocan con "#", se puede colocar hasta 6 tipos de encabezados cada uno con un "#" más. Siempre debe haber un espacio entre el símbolo "#" y el primer carácter del Heading.  

\# Heading 1  
\## Heading 2  
\### Heading 3  
\#### Heading 4  
\##### Heading 5  
\###### Heading 6  

Otra sintaxis para crear encabezados es con carácteres "=", debajo del texto para un Heading mayor y con "-" para un Headign menor.

Heading 1  
\=======  
Heading 2  
\------------

## Paragraphs (Párrafos)

Para crear párrafos se debe dejar una línea entre el texto que estás escribiendo como por ejemplo se verá a continuación.

Dejando una línea como se ve anteriormente se crea un nuevo párrafo. Esto es muy diferente a los salto de línea que se verán en la siguiente parte.

## Line Breaks (Saltos de Línea)

Estos se refieren a comenzar el texto en una nueva línea.
Si únicamente damos un espacio como con la línea anterior y esta, texto continuará en un mismo párrafo. (Aquí hay dos espacios al final).  
Para continuar en una nueva línea se debe de dar dos espacios al finalizar una oración y de esta manera se continuará en una nueva línea sin dejar espacios como en los párrafos.

## **Bold (Negrita)**

Para escribir en negrita debemos de colocar dos asteriscos "\*" al inicio y al final de lo que deseemos que esté en negrita. También se puede colocar dos barras bajas "_"; sin embargo para realizarlo sobre caracteres dentro de una sola palabra solo se usa asteriscos "\*".

**Negrita con 2 Asteriscos**  
__Negrita con 2 Barras Bajas__  
N**egr**ita de c**aracte**res 

## *Italic (Cursiva)*

Para escribir en cursiva debemos de colocar un asterisco "\*" al inicio y al final de lo que deseemos que esté en cursiva. También se puede colocar una barra baja "_"; sin embargo para realizarlo sobre caracteres dentro de una sola palabra solo se usa el asterisco "*".

*Cursiva con 1 Asterisco*  
_Cursiva con 1 Barra Baja_  
Cu*rsi*va de c*aracte*res 

## ***Bold and Italic***

Se colocan tres asteriscos o barras bajas; de igual manera para carácteres entre palabras solo se usa los asteriscos.

***Negrita y Cursiva con 3 Asteriscos***  
___Negrita y Cursiva con 3 Barras Bajas___  
Ne***grita y Cursi***va de c***aracte***res

> ## BlockQuotes (Citas de bloque)
> Son citaciones o tambien texto que resalta por encima de los demás, para crear una BlockQuote, se debe colocar el símbolo ">" al incio de una línea.
>
> Como se puede ver se puede crear de todo dentro de una BlockQuote, desde párrafos hasta incluir Headings como se ven en este ejemplo.
>
> Los símbolos de ">" deben continuar apareciendo en el inicio de las líneas hasta que se quiera cerrar la BlockQuote.
>
> >## BlockQuotes Anidadas
> >
> >Dentro de una BlockQuote también se puede colocar más de estas colocando otro símbolo ">>" al inicio de la línea deseada.
> > 
>

## Orderer Lists (Listas Ordenadas)

Para crear una lista ordenada se debe colocar el número uno seguido inmediatamente de un punto y luego un espacio. Se puede continuar la lista en orden numérico pero incluso si colocas números en desorden se verá una lista ordenada. Para crear identación usamos Tab.

1. Uno
2. Dos
9. Tres  
   1.  Tres Punto Uno
   2.  Tres Punto Dos

## Unorderer Lists (Listas Ordenadas)

Para crear una lista ordenada podemos usar 3 tipos diferentes de símbolos: el asterisco "*", el símbolo de suma "+" y el símbolo de resta "-" . Se recomienda siempre usar del mismo tipo. La identación se realiza de la misma manera.

* Primero
* Segundo
* Tercero
  + Primero del Tercero
  + Segundo del Tercero

## Lists Elements (Elementos de Lista)

Se pueden añadir elementos dentro de un elemento de una lista, como párrafos, BlockQuotes u otros elementos que veremos luego para esto debemos asegurarnos de dejar una línea en blanco y dar un Tab luego del elemento de la lista para mantener el orden y la referencia.

1. First
2. Second

    Parrafo dentro de un elemento de una lista.

3. Third

    > BlockQuote dentro de un elemento de una lista.

4. Fourth

## Code (Código)

También se puede colocar texto en forma de código, para esto se usan los acentos simples o dobles `code`, ``morecode``

Se pueden generar bloques completos de código para esto se usa la identación con 2 Tabs como si realizaramos programación de verdad.

    # Código en Python
    a = 2   
    b = 5
    print(a+b)

## Horizontal Rules (Reglas)

Para colocar una regla horizontal como la que se puede ver debajo de los Headings 1 y 2, se puede colocar tres asteriscos, guiones bajos o guiones comunes.

***
---
___

## Links

Para colocar links se usa las siguiente sintaxis: Colocar el texto que desees que posea un link entre corchetes "[ ]", inmediatamente después colocar el link entre paréntesis "( )".

[Guia de Markdown](https://www.markdownguide.org/)

También se le puede añadir un título al los links, es decir que te muestren un mensaje en lugar de el link. Para esto se coloca dentro de los paréntesis del link, el título entre comillas.

[Guia de Markdown](https://www.markdownguide.org/ "Esto te llevará a la gúia de Markdown")


## URLs / Emails

Para colocar urls o direcciones de email rápidamente y sin estar colocadas en un texto se colocan estos links dentro de paréntesis angulares "<>"

<joao.quispeh22@gmail.com>  
<https://www.markdownguide.org> 

Los links de todo tipo pueden tener formato de negrita cursiva o en código.

**[Guia de Markdown](https://www.markdownguide.org/)**  
*<joao.quispeh22@gmail.com>*  
[`Guia de Markdown`](https://www.markdownguide.org/)

## Reference Links

Se puede crear también links en los cuales se referencie el url aunque este se encuentre más adelante o al final. Para esto se coloca el texto dentro de corchetes y luego otros corchetes con un número; por ejemplo, a continuación se verá un link de la [Guía de Markdown][1].

[1]: https://www.markdownguide.org "Esto te llevará a la gúia de Markdown"
