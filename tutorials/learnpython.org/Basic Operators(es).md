Operadores Básicos
---------------  

Tutorial
--------

esta sección explica un poco sobre como usar los operadores básicos en Python. 

### Operadores Aritméticos  


Tal como cualquierr otro lenguaje de programacion, los operadores de sumas, restas, multiplicaciones y divisiones pueden ser usadas con números.<br> 

	numeros = 1 + 2 * 3 / 4.0   

Intenta predecir que la respuesta será. Si python sigue las ordenes de los operadores?

Otro operador disponible es el de modulo (%), este regresa el integral remanente de una división. dividendo % divisor = remanente.
	
	remanente = 11 % 3

Usando dos simbolos de multiplicación crea una relación de potencia.

	cuadrado = 7 ** 2 
	cubico = 2 ** 3

### Usando operadores con texto

Python soporta unir texto usando el operador de adición:

	holamundo = "hola" + " " + "mundo"

Python también soporta multiplicar texto o cadenas para formar una cadena con una secuencia repetitiva:

	muchosholas = "hola" * 10

### Usar Operadores con listas

Listas pueden ser unidas con los operadores de adición:

	even_numbers = [2,4,6,8]
	odd_numbers = [1,3,5,7]
	all_numbers = odd_numbers + even_numbers

Just as in strings, Python supports forming new lists with a repeating sequence using the multiplication operator:

	print [1,2,3] * 3

### Ejercicios

The target of this exercise is to create two lists called x_list and y_list, which contain 10 instances of the variables x and y, respectively. You are also required to create a list called "big_list", which contains the variables "x" and "y", 10 times each, by concatenating the two lists you have created.

Tutorial Code
-------------

	x = object()
	y = object()
	
	# change this code
	x_list = [x]
	y_list = [y]
	big_list = []
	
	print "x_list contains %d objects" % len(x_list)
	print "y_list contains %d objects" % len(y_list)
	print "big_list contains %d objects" % len(big_list)
	
	# testing code
	if x_list.count(x) == 10 and y_list.count(y) == 10:
	    print "Almost there..."
	if big_list.count(x) == 10 and big_list.count(y) == 10:
	    print "Great!"

Expected Output
---------------

	x_list contains 10 objects
	y_list contains 10 objects
	big_list contains 20 objects
	Almost there...
	Great!