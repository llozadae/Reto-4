Reto 4

A continuación comparto lo correspondiente a este reto 

# Pseudocódigo números primos
print ("Reto 4")
Variables
num = int
x = int
contador = int
Ingrese un numero
a : int = int(input("Ingresa un numero"))
#Inicializamos n en cero
num = 0
while a>0:
    num = num + 1
    x = 1 #Inicializamos x en uno
    contador = 0 #Inicializamos contador en cero
    while x<=num:
        if num % x == 0:
            contador = contador + 1
        break
    x = x + 1 #Incrememtamos la variable x
    break
    if contador == 2:
        print("El numero ",num,"es primo")
        a = a - 1
# Diagrama de flujo 
<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/7LQ1KqFg/Diagrama-sin-t-tulo-drawio.png' border='0' alt='Diagrama-sin-t-tulo-drawio'/></a>

# Pseudocodigo raiz cuadrada
import math
n = float( input("Digite un número:  "))
y = math.sqrt(n)
while n<=0:
    print("Error: Debe ser un número positivo")
    print ("Recuerda que no existe la raiz cuadrada de los número negativos")
    print("Digite un numero: ")
print("Su raiz cuadrada es:") 
print(y)
# Diagrama de flujo
<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/Yqp4LJVk/Diagrama-sin-t-tulo-drawio-1.png' border='0' alt='Diagrama-sin-t-tulo-drawio-1'/></a>