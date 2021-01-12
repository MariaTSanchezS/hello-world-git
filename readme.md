# Version del curso
version actual v1.2.2

# Cabecera H1
## Cabezera h2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6


underline 1
---------------
underline 2
========

- Formato *italica* de la primer forma
- Formato _italica_ de la segunda forma
- Formato **bold o strong**
- Formato __bold o strong__
- Formato ~~tachado~~
- Aca podemos usar *italica* y ~~tachado~~

# listas
esto es un item de lista ordenada
1. Esto es un item
1. Esto es un item
1. Esto es un item
- Lista desordenada
- Lista desordenada
- Lista desordenada
esto es un item de lista desordenada

# Links
- <a href="www.google.cl">Link HTML</a>
- [Esto es un link en markdown](www.google.com)
- [Esto es un link al index](index.html)

# Imagenes
![logo github]()

# Code Snippets
~~~JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
~~~
~~~Javascript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
~~~
# Tablas
|nombre |apellido|
__________________
|javi |velasquezs|
