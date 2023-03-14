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
para ello, se insertan tres variales en las cuales el usuario pueda introducir esos tres numeros
