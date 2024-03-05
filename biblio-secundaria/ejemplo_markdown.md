# Guía Rápida de Markdown
Aparte de ser una guía rápida, la idea es que sea un ejemplo de uso para esta forma de construir documentos.

# Encabezados
Los encabezados no son una manera de cambiar el tamaño de la letra, sino que es un modo de estructurar jerárquicamente los temas de lo que estamos escribiendo.

En donde el nivel 1 es el nivel de mayor "importancia", y los siguientes, dependen de este.

### Código
```
# Nivel 1

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 

## Nivel 2

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 

### Nivel 3

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 

#### Nivel 4

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 

##### Nivel 5

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 

###### Nivel 6

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
```
### Vista previa
# Nivel 1

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 

## Nivel 2

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 

### Nivel 3

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 

#### Nivel 4

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 

##### Nivel 5

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 

###### Nivel 6

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 

# Párrafos
Para que git pueda hacer mejor su trabajo, limiten el ancho de las líneas a 80 caracteres, de esta forma pueden reducir la probabilidad de cambios superpuestos. Esto también facilita leer el archivo en   consola, pero es preferible _arrancar_ por el motivo más técnico.

Esto no trae cambios en el formato que vemos luego en markdown, ya que las líneas consecutivas son tratadas como un único párrafo.

## "Formato"

### Código
```
Énfasis con *asteriscos* o _guion bajo_. Se traduce a itálica.

El énfasis fuerte es por medio de **asteriscos dobles**  o __guion bajo doble__. Se traduce a negrita

O enfasis doble, con ***triple asterisco***, que es simultáneamente negrita e itálica

Esto es combinable vía **asteriscos y _guión bajo_**.

Es posible 'tachar'con doble virgulilla ~~Como esto~~.
```
### Vista previa
Énfasis con *asteriscos* o _guion bajo_. Se traduce a itálica.

El énfasis fuerte es por medio de **asteriscos dobles**  o __guion bajo doble__. Se traduce a negrita

O enfasis doble, con ***triple asterisco***, que es simultáneamente negrita e itálica

Esto es combinable vía **asteriscos y _guión bajo_**.

Es posible 'tachar'con doble virgulilla ~~Como esto~~.

## Texto pre-formateado
El texto pre-formateado es utilizado para bloques de código de programa, en estas secciones, no se aplicará formato.
Pero es posible indicar el lenguaje de programación para que su sintaxis tenga colores.

Estas secciones comienzan y terminan con "acento grave" o "backtick"  ` 

```
``python
def saludar(mensaje):
	print(f"Hola {mensaje}")
``
``
def saludar(mensaje):
	print(f"Hola {mensaje}")
``
```
### Vista previa
```python
def saludar(mensaje):
	print(f"Hola {mensaje}")
```
```
def saludar(mensaje):
	print(f"Hola {mensaje}")
```
*este texto estará en cursiva*
_este texto también estará en cursiva_
**este texto estará en negrita**
__este texto también estará en cursiva__
*También es posible **combinarlos***
_También __es__ posible combinarlos_

### Como parte de un párrafo
Este mismo carácter se puede emplear para palabras y frases dentro de un párrafo normal, para indicar programas o fragmentos de uno, por ejemplo:

Para buscar archivos, podemos llamar a `grep -e`, que nos permite hacer búsquedas con expresiones regulares, o *RegEx*
Para obtener información del usuario en Python, una opción, es con el *buit-in* `entrada = input(mensaje)`.

Desafortunadamente, cuando es usado de esta manera, no hay forma de indicar el lenguaje como con los bloques, por lo que no tendrá "resalte" en colores.

## Citaciones

### Cita en bloque
Nos es posible indicar que hemos copiado textualmente el texto de otro, como una cita textual, la cual comienza con el carácter `>`.

### Código
```
> Si he visto más lejos ha sido porque he estado subido a Hombros de Gigantes.
   Isaac Newton
```
### Vista previa
> Si he visto más lejos ha sido porque he estado subido a Hombros de Gigantes.
   Isaac Newton

### Citas en contexto
 en contexto
Para las citas, hace falta un poco de trabajo adicional, pero el resultado queda muy bien.
Por un lado, es necesario incorporar un enlace interno a la bibliografía: [[1]](#1) / `[[1]](#1)`. Un par de corchetes de la parte izquierda de este enlace es el texto del mismo, miren que en este caso, incluye un par de corchetes en sí.

Esta parte, puede ser cualquier texto y si desean utilizar otro estilo de citas, lo pueden reemplazar, por ejemplo [(Github flavored markdown spec, s. f.)](#1)/`[(Github flavored markdown spec, s. f.)](#1)`

### Código

### Vista previa
Este párrafo contiene una cita a una famosa publicación de Dijkstra, en la cual expresa que "la sentencia **go to** debiera ser abolida..." [[1]](#1), y aunque está sacada de contexto, la situación a la que se llega esta conclusión deja lugar a su utilización y no a su abolición completa, da un buen ejemplo de como referenciar una publicación en contexto.

## Bibliografía

<a id="1">[1]</a> Github flavored markdown spec. (s. f.). Recuperado 28 de junio de 2022, de https://github.github.com/gfm/

<a id="2">[2]</a> Dijkstra, E. W. (1968). Go to statement considered harmful. Communications of the ACM, 11(3), 147-148.
