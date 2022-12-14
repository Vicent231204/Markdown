# MARKDOWN

Markdown es un lenguaje de mercado ligero, una forma de agregar formatos como encabezados,negritas, cursivas,listas... a un texto sin formato utilizando un editor de texto simple. Es decir, una forma rápida de coger apuntes con ordenador y pasarlos a limpio en un solo paso.

    - Elementos de bloque
      - Párrafos
      - Saltos de línea
      - Encabezados
      - Citas
      - Listas
      - Códigos de bloque
      - Líneas horizontales
    - Elementos de línea
      - Énfasis
      - Links o enlaces
      - Código
      - Imágenes
    - Otro elementos
      - Limks automáticos
      - Omitir Markdown
      - Símbolos matemáticos      

# Saltos de bloque (=Párrafos)

Para generar un nuevo párrado en Markdown simplemente separa el texto mediante una línea en blanco (pulsando dos veces INTRO). `Ejemplo:`

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s

# Saltos de línea (=lineas de texto)

Para realizar un salto de línea y empezar una frase en una línea siguiente dentro del mismo párrafo, tendrás que pulsar **dos veces** la barra espaciadora antes de pulsar una vez INTRO. `Ejemplo`

Nombre:  
Apellidos:  
Dirección:

# ENCABEZADOS

Las almohadillas o o hastag `#` es el metodo utilizado en Markdown para crear encabezados. Debes usarlos añdiendo uno por cada nivel y dejando un espacio en blanco.
`Ejemplo:`

## Encabezado 2

### Encabezado 3

#### Encabezado 4

##### Encabezado 5

###### Encabezado 6

# Enfatizar: negritas y/o cursivas

Para poner cursivas encierra entre 1 asterisco Para poner negritas encierra entre 2 asteriscos. Para poner negritas y cursiva encierra entre 3 asteriscos `Ejemplos:`

Lorem *Ipsum* is **simply** dummy text of the printing and ***typesetting*** industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s

# Líneas horizontales

Para crearlas, en una línea en blanco deberás incluir `tres` de los siguientes elementos: 3 asteriscos, 3 guiones, o 3 guines bajos. `Ejemplo:`

***

# Citas 

Las citas se generar utilizando el carácter mayor que `>` al comienzo del bloque de texto. `Ejemplo:`

> Lorem ipsum dolor sit, amet consectetur adipisicing elit. Enim quibusdam reprehenderit eum magni minima eaque impedit reiciendis ullam asperiores fugit. 


# Listas 

Para crear listas desordenadas podemos utilizar 3 tipos de simbolos para cada item de la lista: Un asterisco `*`, un guión medio `-` o un simbolo más `+`.`Ejemplo:`

* ítem 1
* ítem 1
* ítem 1

Para crear listas ordenadas debes utilizar la sintaxis de tipo: `1.`.

1. ítem 1
2. ítem 1
3. ítem 1

Para generar listas anidadas (desordenadas u ordenadas) dentro de otras, simplemente tendrás que añadir `dos (o cuatro) espacios en blanco`.`Ejemplo:`

* ítem 1
  * ítem 12
     * ítem121
* ítem 2

1. etem 1
     ítem 12
2. ítem 1

# Links o enlaces 

Se crean esbribiendo la palabra o texto enlazada entre `[]` corchetes, y el link en cuestión entre `()` paréntesis.

Sin texto enlazado escribe la URL entre ángulos `<URL>` Enlace de ejemplo como referencia: [3con14](https://youtube.com)

#Imágenes

Insertar una imagen con Markdown se realiza de una manera idéntica  a insertar links. En este caso añadir un simbolo de `!` exclamación al principio y el enlace que es la ubicación de la imagen.

`![Texto alternativo](ruta/imagen.jpg "Titulo alternativo")`

`Ejemplo:`
![Imagen cursed](cursed.jpg "No se lo que es ")
![Imagen cursed](cursed2.jpeg)

# Tablas

Markdown permite dibujar mediante plecas `|`. Cada celda está separada por uno de estos caracteres. Para crear encabezados que se distingan visualmente del resto del contenido, se subrayan las celdas correspondientes con guiones `-`.`Ejemplo:`

| **Columna1** | **Columna 2** |
|--|--|
| uno| dos |
| tres | cuatro |
| cinco | seis|

# Línea de Código

Encerrado el código entre acentos graves `<html lang="es">`

# Bloque de Código

Para crear un bloque entero que contenga código lo único que tienes que hacer es encerrar dicho párrafo entre dos líneas formadas por tres ~ virgulillas o tres acentos grave. La otra manera de añadir código en Markdown es comenzar el párrafo con `cuatro espacios en blanco`.`Ejemplo:`

~~~html   
<head> 
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <title>Document</title>
</head>
    
~~~

# Omitir Markdown

Cómo escribir ciertos simbolos como *o #, sin que Markdown los interprete para convertirlos en negritas,...
Escribiendo justo del simbolo la barra invertida `\`.`Ejemplo:` Esto es un asterisco *

# Escritura matemática 

En linea encerrando la fórmula entre signos de `$` En párrafos centrados, encerrando las fórmula entre dos signos de `$$`

* Fórmulas en línea: $(a + b)² = (a+b)*(a-b)$
* Fórmulas centradas:
 $$ a²-b² = (a+b)*(a-b)$$

* Radicales:
  $$ \sqrt {a²-b²} \ $$

* Fracciones
  $$ x=\frac {-b ± \sqrt {b²-4ac}}{2a}$$
* Paréntesis grandes:
 $$ \left( \sqrt {x²}\right)²  $$
* Colores
  $$ {\color{yellow}{A}}aBb123$$
