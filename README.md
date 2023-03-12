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
