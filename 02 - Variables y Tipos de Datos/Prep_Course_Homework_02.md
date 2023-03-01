## Variables

1) Crear una variable que contenga un elemento del conjunto de números enteros y luego imprimir por pantalla

    a=12
    print(a)

2) Imprimir el tipo de dato de la constante 8.5

type(8.5)

3) Imprimir el tipo de dato de la variable creada en el punto 1

type(a)

4) Crear una variable que contenga tu nombre

nombre = 'Emi'

5) Crear una variable que contenga un número complejo

numero_Complejo = 0 + 2j

6) Mostrar el tipo de dato de la variable crada en el punto 5

print(type(numero_Complejo))

7) Crear una variable que contenga el valor del número Pi redondeado a 4 decimales

pi_redondeado = 3.1415

8) Crear una variable que contenga el valor 'True' y otra que contenga el valor True. ¿Se trata de lo mismo?

var1='True'
var2=True

9) Imprimir el tipo de dato correspondientes a las variables creadas en el punto 8

print('La variable 1 es de tipo ', type(var1), ' y la variable 2 es de tipo ', type(var2))

10) Asignar a una variable, la suma de un número entero y otro decimal

suma_Ent_Dec = 2+5.5

11) Realizar una operación de suma de números complejos

a=1+4j
b=4+7j
print(a+b)

12) Realizar una operación de suma de un número real y otro complejo

a= 4
b= 3+7j
print(a+b)

13) Realizar una operación de multiplicación
a=3
b=4
print(a*b)

14) Mostrar el resultado de elevar 2 a la octava potencia

print(2**8)

15) Obtener el cociente de la división de 27 entre 4 en una variable y luego mostrarla

a=27
b=4
cociente=a/b
print(cociente)

16) De la división anterior solamente mostrar la parte entera

cociente_entera=a//b
print(cociente_entera)

17) De la división de 27 entre 4 mostrar solamente el resto

cociente_resto=a%b
print(cociente_resto)

18) Utilizando como operandos el número 4 y los resultados obtenidos en los puntos 16 y 17. Obtener 27 como resultado

    4*6+3

19) Utilizar el operador "+" en una operación donde intervengan solo variables alfanuméricas

var1='Hola '
var2='mundo'
print(var1 + var2)

20) Evaluar si "2" es igual a 2. ¿Por qué ocurre eso?

"2"==2 False

21) Utilizar las funciones de cambio de tipo de dato, para que la validación del punto 20 resulte verdadera

2==int('2')=True

22) ¿Por qué arroja error el siguiente cambio de tipo de datos? a = float('3,8') 

No se puede transformar el dato string a float

23) Crear una variable con el valor 3, y utilizar el operador '-=' para modificar su contenido

a=-3
b-=1
print(a)
=-4

24) Realizar la operacion 1 << 2 ¿Por qué da ese resultado? ¿Qué es el sistema de numeración binario?

1<<2=4

25) Realizar la operación 2 + '2' ¿Por qué no está permitido? ¿Si los dos operandos serían del mismo tipo, siempre arrojaría el mismo resultado?

Al no poder hacerse operaciones con diferentes tipos de datos.

26) Realizar una operación válida entre valores de tipo entero y string

var1= 'Hoy me picaron '
var2= 5
print(var1 + str(var2) + ' mosquitos '*var2)