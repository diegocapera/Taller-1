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
  

