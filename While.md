#Requerimientos del cliente:

#Desarrollar un programa que permita al usuario ingresar un número entero positivo y luego imprima la tabla de multiplicar de ese número hasta el 10.

#Pedir al usuario que ingrese un número entero positivo
num = int(input("Ingrese un número entero positivo: "))

#Verificar si el número es positivo
while num <= 0:
    print("Error: el número debe ser positivo.")
    num = int(input("Ingrese un número entero positivo: "))

#Imprimir la tabla de multiplicar del número hasta el 10
i = 1
while i <= 10:
    print(f"{num} x {i} = {num * i}")
    i += 1
