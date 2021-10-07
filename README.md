# edades
"""operadores de comparacion

> = menor igual
< = mayor igual
== igualdad
! = diferencia
< menor
> mayor

Escribir un programa que evalue e imprima la edad de una persona
si es mayor o igual a 18 es mayor de edad si es menor de 18 es menor de edad"""

edad = int(input('Escriba su edad:'))

if(edad >= 18):
    print('su edad es: ', edad, 'por lo tanto es mayor de edad')
else:
    print('Su edad es:', edad, 'por lo tanto es menor de edad')

