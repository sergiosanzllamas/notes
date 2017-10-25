# Terminal

## Redirecciones

&gt; redireccion de salida. Crea un fichero nuevo.

&gt;&gt;: Doble redireccion d S. anexa un fichero.

&lt; : Redirigir la entrada.

&lt;&lt; : here document.

&lt;&lt;&lt; : here string.

2>: redirigir stderr
|: pipe, tuberia(usa en secreto un fichero anonimo)

redireccion de copia


## Variables

#: cantidad de parametros

## metacaracteres

~: directorio home
.: directorio actual
. .: el directorio de arriba
-: el fichero que representa a la terminal
$: lo que vale la variable.
" ": es un caracter que tiene poderes especiales partir palabras
\\: scuencia escape = criptonita de los metacaracteres.
"". quitan el poder a casi todos los metacaracteres menos al $
'': quita el poder a todos los meta.
\*: cualquier secuencia de caracteres.
?: cualquier caracter.
[]: conjunto de seleccion.
{}: combinaciones de frecuencias.

## otros



#! Shebang: interprete con el que hay que ejcutar el archivo.
! !: el ulrimo comando.
! \*: los ultimos parametros

&&. and
| |: or 
!: not 