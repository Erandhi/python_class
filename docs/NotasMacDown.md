#Notas de MacDown (título)
##Clase 1 25/febrero/2021

Los comandos revisados se encuentran en el GitHub [link cheatsheet] (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
### Listas y palabras
##Subtitulo 1
###subtítulo 2
####Subtitulo 3
#####Subtítulo 4...etc 

* Poner en italicas *hola*
	* sublista (tab)
* Poner en negritas **hola**

	párrafo identado (espacio, tab-texto, espacio)
	
* Tachar la palabra ~~hola~~ 


1. item 1
2. item2
3. item 3

###Enlaces

[Nombre que recibirá el enlace al URL](URL)

Por ejemplo, el siguiente texto es del cheatsheet:

[I'm an inline-style link](https://www.google.com)

aquí cuando el cursor está sobre el texto que lleva al url (sin hacer click) marca que es la página de google:

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../blob/master/LICENSE)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com

###Imágenes

![describen la imagen] (https://ar.zoetis.com/_locale-assets/mcm-portal-assets/publishingimages/especie/caninos_perro_img.png)  

###Escribir Código

Para ver lista de direcctorios `ls` 
directorio de trabajo `pwd`

Mi scrip es el siguiente. 

```
 ls
 cd
 mkdir tmp 
```
```python
5+5
hola
```
###Tablas
Al menos poner tres rayas --- para que detecte que será tabla, los dos puntos : son para indicar si el testo va centrado o a la derecha, sin untos por default manda el texto a la izquierda.

| Tables        | Are           | Cool  |
| --- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |





