# Taller-1
Taller 1, hecho por Diego Alejandro Gutierrez Capera para la materia de programación de computadores grupo 6 UNAL
1) Quiz con resultado de 95% de aciertos
![image](https://user-images.githubusercontent.com/124608110/224910882-14d1470d-c455-439f-bec8-cd23951681c4.png)

2)Realice un programa que lea tres números reales y determine cuál es el mayor.
```python
# Pedir tres numeros al usuario
n1 = float(input("Introduce el primer numero: "))
n2 = float(input("Introduce el segundo numero: "))
n3 = float(input("Introduce el tercer numero: "))

# Comparar los tres numeros para determinar el mayor
if n1 >= n2 and n1 >= n3:
    print("El numero " + str(n1) + " es el mayor")
elif n2 >= n1 and n2 >= n3:
    print("El numero " + str(n2) + " es el mayor")
else:
    print("El numero " + str(n3) + " es el mayor")
print
```
En este ejercicio lo que se busca es que el usuario pueda introducir los numero que el quiera y mediante este codigo determine cual es el mayor,
para ello, se insertan tres variales en las cuales el usuario pueda introducir esos tres numeros, seguido a ello entra a comparar los numeros mediante la palabra reservada "if" si se cumple en un primer caso, si no se recurre a la palabra "elif", la cual se puede repetir las veces necesarias, pero si no se cumple en esas veces necesarias el programa se vera forzadoa utilizar el ultimo que "else", el cual se le asigna un mensaje en el caso en el que no se cumpla ningun caso.

3)Realice un programa que lea un número enteros y determine si es par o impar.
```python
# Pedir tres numeros enteros al usuario
alpha = int (input("Introduce un numero entero: "))
beta = int (input("Introduce un numero entero: "))
gamma = int (input("Introduce un numero entero: "))

# Comparar si alpha es par o impar
if alpha % 2 == 0:
  print("El numero " + str(alpha) + " es par")
else:
  print("El numero " + str(alpha) + " es impar")

# Comparar si beta es par o impar
if beta % 2 == 0:
  print("El numero " + str(beta) + " es par")
else:
  print("El numero " + str(beta) + " es impar")

# Comparar si gamma es par o impar
if gamma % 2 == 0:
  print("El numero " + str(gamma) + " es par")
else:
  print("El numero " + str(gamma) + " es impar")
 ```
 En el siguiente caso lo que se hace es pedirle al usuario tres numeros enteros los cuales se forzaran a ser asi con la palabra reservada int, seguido a ello, se entra a comparar a cada uno con la palabra reservada "if", seguido a ello se pone el nombre de la variable donde esta contenida el numero y se somete a una de las funciones la cual es el modulo % en el cual se condiciona con un comparador "==" para dar la condicional, que en este caso es si es 0, entonces es par, pero en el caso de que no lo sea, se da directamente con la palabra reservada "else" seguido a un mensaje declarando es es impar.
 
 4)Realice un programa que lea dos números reales y determine si el primero es múltiplo del segundo.
 
 ```python
 #Pedir dos numeros reales
alpha = float(input("Inserte un numero real:"))
beta = float(input("Inserte un numero real:"))

#Comparar si el numero alpha es multiplo de beta
if alpha*2 == beta:
  print("El numero " + str(alpha) + " es multiplo de " + str(beta))
else:
  print("El numero " + str(alpha) + " no es multiplo de " + str(beta))
print
```
En el siguiente punto se le pide al usuario dos numeros reales y para forzar esa condicion se impone la palabra "float" para declarar que esa variable será una variable con número real, despues se comprar si el número el cual se llama "alpha" es multiplo de "beta" y para ello se multiplica por 2 y seguido a ello se compara con "beta" para saber si el primer caso se cumple, en el caso de que si se deja un mensaje confirmando que es multiplo, en el caso contrario se deja otro mensaje declarando que no es multiplo 

5)Realice un programa que lea tres números reales y determine si la suma de los dos primeros es mayor, menor o igual que el tercer número.

```python
#Pedir al usuario los numeros
alpha = float(input("Inserte un numero real: "))
beta = float(input("Inserte un numero real: "))
gamma = float(input("Inserte un numero real: "))

#Sumar y comparar si alpha y beta es mayor que gamma
sum = alpha + beta
if sum > gamma:
  print("La suma de " + str(alpha) + " mas " + str(beta) + " es mayor que " + str(gamma))
elif sum < gamma:
  print("La suma de " + str(alpha) + " mas " + str(beta) + " es menor que " + str(gamma))
else:
  print("La suma de " + str(alpha) + " mas " + str(beta) + " es igual que " + str(gamma))
 ```
 En este punto se le pide al usuario tres numeros, los cuales seran sumados "alpha" y "beta", y dependiendo de su resultado cumpliran las condicionales dadas y dependiendo de cual cumpla o si no cumple ninguna, mostrará alguno de los tres mensajes confirmando si la suma de los numeros ingresados en las variables "alpha" y "beta" son mayor, menor o igual al numero ingresado en la variable "gamma"
 
 6)Escriba un programa que solicite al usuario una letra y determine si es una vocal o una consonante.
 ```python
 # Pedir al usuario una letra
lang = input("Inserte una letra: ")

#Comparar si la letra es vocal
if lang == ["a", "e", "i", "o", "u"]:
    print("La letra ingresada es una vocal")
else:
    print("La letra ingresada es una consonante")
 ````
En este ejercicio, simplemete se busca una comparacion, donde se deja las vocales en un primer caso donde si se cumple, será una vocal y si no, entonces seria una consonante.

7)Escriba un programa que pida 5 números reales y calcule las siguientes operaciones:

El promedio
```python
#Pedir cinco numeros al usuario
from statistics import median


a : float
a = float(input("Inserte un numero: "))
b : float
b = float(input("Inserte un numero: "))
c : float
c = float(input("Inserte un numero: "))
d : float
d = float(input("Inserte un numero: "))
e : float
e = float(input("inserte un numero: "))


#Promedio
promedio : float = ((a)+(b)+(c)+(d)+(e))/5
print("El promedio de los numeros es " + str(promedio))
```
En este punto, se le pide inicialmente cinco numeros al usuario, los cuales se trabajaran con todos los codigos en este punto, lo siguiente es calcular el promedio, donde se ponen a las cinco variables y se suman, por ultimo se duviden en el numero de datos y se muestra el mensaje del promedio de esos cinco valores.

La mediana
```python
#Mediana
li = (a, b, c, d, e,)
mediana = median(li)
print("la mediana de los numeros ingresados son :", mediana)
```
En el siguiente punto, se toman los 5 valores como se dijo anteriormente y se pocede a sacar la mediana, la cual aqui se usa la palabra reservada "median" y la variable que contiene los cinco valores que van a tener 

Promedio multiplicativo
```python
#Promedio multiplicativo
producto = a*b*c*d*e
promedio_multiplicativo = producto**(1/5)
print("El promedio multiplicativo es: ",promedio_multiplicativo)
```
En este punto se realizó con dos variables las cuales la primera es donde se multiplican los cinco numeros ingresados por el usuario y seguido a ello esa variable es ingresada dentro de otra variable, donde se someterá a la raiz quinta ya que ese es el numero de datos y por ultimo se imprime el resultado de esa ultima variable.

Orden ascendente
```python
#Ordenar los numeros ascendente
if a > b:
    a, b = b, a
if b > c:
    b, c = c, b
if c > d:
    c, d = d, c
if d > e:
    d, e = e, d
if a > b:
    a, b = b, a
if b > c:
    b, c = c, b
if c > d:
    c, d = d, c
if a > b:
    a, b = b, a
if b > c:
    b, c = c, b
if a > b:
    a, b = b, a
print("Los números ordenados de forma ascendente son:")
print(a, b, c, d, e)
```
En el siguiente punto se comparan todos los valores donde en un primer listado se comparan cada uno y se repite la secuencia pero eliminando el ultimo valor, y asi sucesivamente hasta comparar el primer valor con el segundo para determinar quien es mayor.

Orden descendente
```python
#Ordenar los numero de forma descendente
if a < b:
    a, b = b, a
if b < c:
    b, c = c, b
if c < d:
    c, d = d, c
if d < e:
    d, e = e, d
if a < b:
    a, b = b, a
if b < c:
    b, c = c, b
if c < d:
    c, d = d, c
if a < b:
    a, b = b, a
if b < c:
    b, c = c, b
if a < b:
    a, b = b, a
print("Los numeros ordenados de forma descendente son: ")
print(a, b, c, d ,e)
```
En este punso simplemente es el mismo proceso del anterior, solo que en vez de comparar si quien de los dos valores el es mayor, acá es comparando quien es el menor.

Potencia del mayor número elevado al menor número
```python
#La potencia del mayor número elevado al menor número
max_num = a
min_num = a
if b > max_num:
    max_num = b
if c > max_num:
    max_num = c
if d > max_num:
    max_num = d
if e > max_num:
    max_num = e

if b < min_num:
    min_num = b
if c < min_num:
    min_num = c
if d < min_num:
    min_num = d
if e < min_num:
    min_num = e
resultado = max_num**min_num
print("El resultado de elevar el " + str(max_num) + " que es el mayor numero con " + str(min_num) + "que es el menor numero es: " + str(resultado))
```

En el siguiente codigo se proponer que el primer numero que se le pide al usuario sera inmediatamente el maximo y el minimo, seguido a ello se comprar los otros 4 valores para determinar quien es el mayor y se repite este proceso para determinar quien es el meno teniendo en cuenta que si se cumple algun caso, se determina que uno de los valores es el reemplazo del primer valor si es el maximo o es el minimo y por ultimo se realiza la operacion deseada teniendo en cuenta que ya estan definidos los valores maximos y minimos.

Calcular la raiz cubica del menor numero
```python
#Calcular la raiz cubica del menor numero
max_num = a
min_num = a
if b > max_num:
    max_num = b
if c > max_num:
    max_num = c
if d > max_num:
    max_num = d
if e > max_num:
    max_num = e

if b < min_num:
    min_num = b
if c < min_num:
    min_num = c
if d < min_num:
    min_num = d
if e < min_num:
    min_num = e
raiz = min_num**(1/3)
print("La raiz cubica del menor numero ingresado es: " + str(raiz))
```
En este caso, simplemente se repite el proseso pero solo se toma el valor mas pequeño entre todos y se realiza la raiz cubica.

8)Escriba un programa al que se le ingrese la frecuencia de una onda en hz y como salida arroje en que parte del espectro electromagnético se encuentra.

```python 
#Pedir un valor en Hz al usuario
frecuencia = float(input("Inserte un valor en Hz: "))

#Comparar si el valor esta en ciertos intervalo
if frecuencia >= 4e14 and frecuencia <= 8e14:
  print("El valor de la frecuencia esta en el rango visible")
elif frecuencia < 4e14:
  print("El valor de la frecuencia esta en el rango de infrarojos ")
else:
  print("El valor de la frecuencia esta en el rango de ultravioleta ")
```
En este punto se le pide al usuario una frecuencia en hertz (Hz) la cual esta alojada en una variable llamada "frecuencia" y esta será comparada con los valores de frecuencia que son visibles al ojo humano, donde si la frecuencia ingresada esta dentro del intervalo de frecuencias del espectro visible, se delara que el valor esta en el rango visible, si esta es menor al intervalo se declara que esta en un rango de infrarojos y si esta es muy alta (superando el intervalo) entonces esta esta en el rango de los ultravioleta.

9)Escriba un programa que reciba el nombre en minúsculas de un país de America y retorne la ciudad capital, si el país no pertenece al continente debe arrojar país no identificado.


