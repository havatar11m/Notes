# Terminal

## Redirecciones

> &gt = Redireccion de salida. Crea un fichero nuevo.
>> &gt &gt = Doble redireccion de salida. Anexa a un Fichero

< &lt = Redirigir la entrada
<< &lt &lt = Here document
<<< &lt &lt &lt = Here string

Cat <[YYYY]> XXXX.me = crea un fichero nuevo que al ejecutarlo con Cat XXXX.me y sale lo que has escrito en "Cat <YYYY"

seq X Y = Te da una secuencia desde X hasta Y

2> = Redirigir stderr

| = Pipe, tuberia (usa fichero anónimo)

Redirección de copia


## Comandos que Unen

Cat = concatenar archivos en terminal
		unir partes/divisiones

paste = Unir en vertical

join = Combinaciones




## Comandos que dividen

tail -2 archivo

tail -f (Deja el fichero abierto)

head

cut = Corta vertical

split = Divide horizontal




## Meta caracteres

$ = Dice el valor de una variable
~ = Mi directorio Home
. = Directorio actual
.. = Directorio de arriba
-- = A veces el fichero 
' ' = Separa palabras
\\ = Secuencia de escape -> Kriptonita de
	los metacaracteres
"" = quitan el poder a casi todos los metacaracteres
	menos al $
\* = Cualquier secuencia de caracter
? = Cualquier caracter
[] = conjunto de selección
{} = combinaciones de secuencias
\` = ejecutar un comando y sustituir por el resultado

## Variable
 
 # = Cantidad de parámetros

## Otros

#! shebang: Intérprete con el que hay que ejecutar el archivo
!! = El ultimo comando
!* = Los últimos parámetros
touch = crea un directorio si no lo hay y si lo hay lo modifica
	la fecha de creación a ese instante


## Operadores Lógicos

&& = AND
|| = or
! = NOT


echo "obase=16; 1389" | bc