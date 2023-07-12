# A comprehensive guide to the ultimate thoughts management app

## Una guía para unificar y comprender el uso de la herramienta (en Castellano, lo de arriba era para darle caché)

### A prueba de [catetos](https://es.wikipedia.org/wiki/Cateto)

### Sin rodeos ni palabras de más

#### Ni títulos de sobra

##### Ni tampoco sub-títulos de sobra

###### Éste ya es por vício

_Nota del editor: Si estás leyendo esto desde GitHub recomiendo encarecidamente que clones el repositorio y lo leas desde Obsidian para tu plataforma. Ya te dejo tranquilo sufrir en paz._

Primero de todo un poco de contexto. Obsidian destaca como un centralizador de ideas, un motor de nodos de pensamiento que nos ayuda a explicar y describir proyectos y a visualizar de forma gráfica y enlazar planes, cavilaciones o apotegmas.

Antes de lanzarnos a conectar ideas hay que repasar las distintas maneras de dar formato al texto que introducimos y a generar dichas conexiones entre nodos.

Como primer consejo, es recomendable introducir siempre un párrafo vacío entre párrafo y párrafo. Grábatelo a fuego.

Cabe destacar también que si hay alguna duda de cómo dar el formato que enseño sólo hay que pinchar sobre el texto en cuestión (o, en algunos casos, pinchar antes o después de dicho texto, como en los enlaces, y movernos al texto con las flechas de dirección). Se mostrarán los caracteres que dan dicho formato.

Podemos usar Tab para generar un párrafo hijo del párrafo anterior.
	Y así sucesivamente con cada párrafo que escribamos.
		Este sería el tercer hijo del primer párrafo.
			Un cuarto hijo para ver cómo se indexa el texto.
				Con las flechitas de la izquierda puedes minimizar los hijos a partir del párrafo cuya flechita has pulsado.
					Ya paro, perdón.

Siguiendo la línea de lo anterior podemos generar citas iniciando el siguiente párrafo con el símbolo >, te lo muestro:

>Este es una cita de ejemplo
>>Y esto es una cita de una cita
>>>Y una cita de una cita de una cita
>>>>History repeats itself

Otra característica es escribir cualquier cosa detrás del # para generar un #Hashtag , o etiqueta de búsqueda. Nos será útil más tarde cuando queramos interconectar ramas.

Al principio podrás comprobar que hay 6 títulos. Está hecho a posta, ahora puedes hacer click sobre el texto que contienen para ver que cada uno es un nivel más bajo que el anterior.

Si iniciamos una línea con # seguido de un espacio, generaremos un título de nivel 1, así:

# Este es el título al que me refiero 

Y si en lugar de uno escribimos tres # (###) seguidos de un espacio, haremos un sub-título de nivel 3, tal que así:

### Un sub-título de ejemplo

Puedes alargar esta historia todo lo que quieras (realmente no, sólo hasta los seis #) si continúas sumándole almohadillas, y cada vez conseguirás títulos más pequeños. Como te digo, funciona hasta el nivel 6 de sub-títulos:

###### Esto es un sub-título 6, con sus seis # 

####### El sub-título 7 no existe, ya te lo he dicho, mira lo que me has hecho hacer

Hasta aquí nos damos cuenta de que cada título a partir del primero (que es el título de la hoja) y cada sub-título nos permite minimizar todo lo que cuelga debajo (con la flechita a la izquierda del título) de forma jerárquica. Si iniciamos un nuevo título o sub-título se romperá dicha minimización, es decir, solo minimizará hasta **aquí**.

# Lo que venga debajo de este título no lo minimiza la flechita del anterior título

Vaya, puse algo en negrita arriba y no expliqué cómo se hace. Es fácil, sólo hay que escribir la cadena de caracteres que queramos resaltar entre cuatro asteriscos (dos al principio y dos al final), es decir, así: ** esto estaría en negrita si no tuviese espacios con los asteriscos ** . Vamos a hacerlo bien, así: **esto sí que está en negrita porque los asteriscos están justo antes y después de la cadena, sin espacios**.

Y podemos hacer exactamente lo mismo para darle formato cursivo, con los símbolos _ _ (misma casuística, la cadena entre dichos símbolos, sin espacios al principio ni al final). Tal que así: _esto estará en cursiva_.

Y ojo que puedes mezclar ambos para resaltar **_cosas muy importantes_**. Yo he usado (** _ ) y (_ ** ) al final (ya sabes, sin los espacios entremedias), pero puedes usar tres asteriscos o tres barras bajas al principio y al final.

Más de lo mismo si queremos introducir un link. Introducimos la cadena entre estos símbolos de dentro del paréntesis ([[]]) y conseguiremos [[esto]]. No le hagas click porfa, te va a llevar a sitios extraños que ni tu ni yo conocemos aún.

_Nota del editor: esto es para crear una hoja con el título que hayas introducido entre los símbolos. No lo he investigado mucho, así que por ahora dejémoslo así y cuando tenga más conocimientos volveremos aquí._

Si en lugar de dos símbolos ([[]]) escribimos sólo uno ([]) conseguimos [esto], que si te digo la verdad no sé muy bien para qué vale. Vamos a investigarlo; después de unos 10 minutos he aprendido que es un enlace y si seguido al corchete no introduces entre paréntesis el enlace al que quieres que apunte, no conseguimos nada. Te lo muestro, sería [así](https://es.wikipedia.org/wiki/Hydrochoerus_hydrochaeris). Y si dentro del paréntesis, justo después del enlace, introduces texto entre comillas dobles, crearás una pequeña etiqueta o título para el enlace. Mira que guay cuando dejas el ratón sobre este [enlace](https://es.wikipedia.org/wiki/Hydrochoerus_hydrochaeris "No son capibaras de nuevo confía en mi")
_Nota del editor: este último punto es ***mentira***, a día 12 de Junio de 2023 aún no se ha implementado esta funcionalidad en la herramienta, pero seguramente lo hará. Lo dejo para no tener que escribirlo de nuevo cuando suceda._ 

Por último quiero destacar el formato para código, no porque sea más importante que el resto de cosas, simplemente porque me gusta. Siguiendo la línea de lo anterior, darle formato a un bloque de código es tan sencillo como introducirlo entre ciertos caracteres (qué sorpresa). Dichos caracteres son (``` ```) al inicio y al final del bloque, sin espacios (haz uso de lo que dije justo al principio y pulsa dentro del paréntesis). Veamos cómo queda:

```
const handleDisplayAll = () => {
	if (records.length === 0) {
		alert('[Empty list]');
		return;
	}
	alert(records);
};
```

Hay mil métodos más para formatear código, por ahora sólo he añadido los que a mi parecer pueden ser más útiles para resaltar ideas, unir conceptos o plasmar ocurrencias. Si el que lea esto considera que es 




