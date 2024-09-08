## Variables

1) Crear una variable que contenga un elemento del conjunto de números enteros y luego imprimir por pantalla

a = 2
print(a)

2) Imprimir el tipo de dato de la constante 8.5

type(8.5)

3) Imprimir el tipo de dato de la variable creada en el punto 1

type(a)

4) Crear una variable que contenga tu nombre

my_name = 'Sandro'

5) Crear una variable que contenga un número complejo

b = 3-2j

6) Mostrar el tipo de dato de la variable crada en el punto 5

type(b)

7) Crear una variable que contenga el valor del número Pi redondeado a 4 decimales

p = 3.1416

8) Crear una variable que contenga el valor 'True' y otra que contenga el valor True. ¿Se trata de lo mismo?

m = True
n = 'True'
# print(type(m))
# print(type(n))
# no son lo mismo, una variable es str y la otra es bool

9) Imprimir el tipo de dato correspondientes a las variables creadas en el punto 8

print('la variable n es de tipo',type(m),'la variable m es de tipo',type(n))

10) Asignar a una variable, la suma de un número entero y otro decimal

var1 = 1 + 2.5
# print(var1)

11) Realizar una operación de suma de números complejos

numc1 = 2 - 3j
numc2 = -5 + 6j
numc1 + numc2

12) Realizar una operación de suma de un número real y otro complejo

numr1 = 1.5
numr1 + numc1

13) Realizar una operación de multiplicación

numc1 = 2 - 3j
numc2 = -5 + 6j
numc1 * numc2

14) Mostrar el resultado de elevar 2 a la octava potencia

print('la potencia de 2 a la 8 es',2**8)

15) Obtener el cociente de la división de 27 entre 4 en una variable y luego mostrarla

div1 = 27/4
print('El cociente de dividir 27 entre 4 es',div1)

16) De la división anterior solamente mostrar la parte entera

div1 = 27/4
print('La parte entera de dividir 27 entre 4 es',27//4)

17) De la división de 27 entre 4 mostrar solamente el resto

div1 = 27/4
print('El resto de dividir 27 entre 4 es',27%4)

18) Utilizando como operandos el número 4 y los resultados obtenidos en los puntos 16 y 17. Obtener 27 como resultado

print('el número 4*6+3=27')

19) Utilizar el operador "+" en una operación donde intervengan solo variables alfanuméricas

stri1 = 'hola'
stri2 = ' mundo'
print(stri1 + stri2)

20) Evaluar si "2" es igual a 2. ¿Por qué ocurre eso?

dos = '2'
dos2 = 2
type(dos) == type(dos2)
print('En este caso el primero es de tipo str y el segundo es de tipo entero')

21) Utilizar las funciones de cambio de tipo de dato, para que la validación del punto 20 resulte verdadera

x = int(dos)
type(x) == type(dos2)

22) ¿Por qué arroja error el siguiente cambio de tipo de datos? a = float('3,8')

print('Por la coma, en este caso a es una cadena no un número, por lo tanto no lo puede convertir a número flotante, para que suceda eso debemos cambiar la coma por punto')

23) Crear una variable con el valor 3, y utilizar el operador '-=' para modificar su contenido

a = 3
a-=1
print(a)

24) Realizar la operacion 1 << 2 ¿Por qué da ese resultado? ¿Qué es el sistema de numeración binario?

1<<2
print('dentro de los números binarios lo que hace esta función es recorrer el número 1 dos lugares hacia')
print('la izquierda, por lo tanto del número 00001 pasa a ser el número binario 01000 que corresponde al')
print(' 4 en el sistema decimal')

25) Realizar la operación 2 + '2' ¿Por qué no está permitido? ¿Si los dos operandos serían del mismo tipo, siempre arrojaría el mismo resultado?

print('no esta permitido ya que son datos de diferentes tipos mientras que 2 es un int, el otro es un str')
print('y de acuerdo a las definiciones de Python no se pueden sumar un stri y un int')
print('si los dos datos fueran del mismo tipo no serían el mismo resulado, por una parte 2+2 = 4 y en el')
print('otro caso es 22')

26) Realizar una operación válida entre valores de tipo entero y string

texto = 'jaja'
num = 5
print(num*texto)
