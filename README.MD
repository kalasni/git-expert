# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5

Underline 1
------------

Underline 2
===========


# Formatos de énfasis

- Letra *itálica* de la primera forma

- Letra _itálica_ de la segunda forma

- Formato **bold o strong** de la primera forma

- Formato __bold o strong__ de la segunda forma

- Formato ~~tachado~~ 

- Podemos usar formato *itálico* pero también **bold**


# Listas

1 Esto es un item

2 Esto es un item

3 Esto es un item

- 4 Esto es un item de lista desordenada


# Links

<a href="www.google.com">Link HTML</a>

[Esto es un link en HTML](www.google.com)

[Esto es un link a index](index.html)


# Imágenes

![Logo de github](https://image.flaticon.com/icons/png/128/24/24233.png)


# Code Snipets

Código en JSON
```JSON
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
```

Código en JavaScript
```JavaScript
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
```


# Tablas

| Nombre | Apellido | DNI |
|--------|----------|-----|
| Pakito | cualquier| 123456789K |
| Zacker | Schildt  | 675746326A |


# Citas

Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita

Esto es otro texto que no se relaciona con la cita anterior.

> Esto es otra cita



# Lineas divisorias

Ésto es un texto que será dividido por guiones medios

---
Ésto es otro texto dividido por asteriscos

***

Éste otro lo será por guiones bajos

___


# Saltos de linea

Éste es nuestro primer párrafo

Éste es nuestro segundo párrafo

Éste es el tercer párrafo