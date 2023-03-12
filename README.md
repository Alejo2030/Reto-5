# Reto-5
## Desarrollo del reto #5 Daniel Alejandro Archila Gómez




***1. Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.***

```ruby
n: int
n= int(input("Escribe un número"))
if n >= 97 and n <= 122:
    print("El número corresponde a una vocal minuscula de ASCII" )
else:
    print("El número no corresponde a una vocal minuscula de ASCII" )
```



***2.Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no.***


```ruby
D=input("Inserte una cadena con longitud 1 =")
numero_ascii= ord (D)

if numero_ascii % 2 == 0 :
    print("El codigo ASCCII de la primera letra es par")
else:
    print("El codigo ASCCII de la primera letra es impar")
```



***3. Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no.***



```d=input("Ingrese un carácter")
ord(d)
n=ord(d)
if n >= 48 or n <=59:
    print("carácter "+str(d)+" es un dígito ")
else :
    print("carácter "+str(d)+" no es un dígito ")
```




***4. Dado un número real x, construya un programa que permita determinar si el número es positivo, negativo o cero. Para cada caso de debe imprimir el texto que se especifica a continuación:***


**Positivo: "El número x es positivo" Negativo: "El número x es negativo" Cero (0): "El número x es el neutro para la suma"**

```ruby
z : float
z = float(input("Ingrese un numero: "))
if z == 0:
    print("El numero "+str(z) + " es el neutro para la suma ")
if z > 0:
    print(" El numero "+str(z)+ " es positivo")
else:
    print("El numero"+ str(z)+ " es negativo")
```



***5.Dado el centro y el radio de un círculo, determinar si un punto de R2 pertenece o no al interior del círculo.***


```ruby
#Coordenadas del circulo
a : float
b : float
#Coordenadas de R2
c : float
d : float 
radio : float 
a = float (input(" Inserte la coordenada en el eje  x del centro del circulo: "))
b = float (input(" Inserte la coordenada en el eje  y del centro del circulo: "))
radio = float(input("Inserte el radio del circulo respectivo: "))
c = float(input(" Inserte la coordenada en el eje x de R2: "))
d = float(input(" Inserte la coordenada en el eje y de R2"))
if((c-a)**2 + (d-b)**2<= (radio) **2):
    print( " los puntos de r2 " +str(c)+ "," +str(d) + " se encuentra en el circulo")  
else: 
     if((c-a)**2 + (d-b)**2>= (radio) **2):
        print(" los puntos de r2 " +str(c)+ "," +str(d) + " no se encuentra en el circulo")
```



***6 .Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo.***
