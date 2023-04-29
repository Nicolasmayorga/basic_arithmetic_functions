# Basic Arithmetic Functions

Este repositorio contiene un conjunto de funciones en Python para realizar operaciones aritméticas básicas como sumar, restar, multiplicar y dividir. Estas funciones trabajan con números del cero al nueve.

## Uso

Importa las funciones desde el archivo `basic_arithmetic.py` y utiliza la siguiente sintaxis para realizar operaciones:


from basic_arithmetic import *

resultado = four(times(five())) # resultado = 20

Funciones disponibles
Números
zero()
one()
two()
three()
four()
five()
six()
seven()
eight()
nine()
Operaciones
plus(y)
minus(y)
times(y)
divided_by(y)
Ejemplos

from basic_arithmetic import *

print(four(times(five()))) # imprime 20
print(one(plus(eight()))) # imprime 9
print(seven(minus(three()))) # imprime 4
print(nine(divided_by(three()))) # imprime 3

