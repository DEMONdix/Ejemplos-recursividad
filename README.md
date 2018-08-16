## Ejemplos-recursividad
  Ejemplos basicos del uso de recursividad
    ##Nicolás Meneses Guerrero 			20161020533
    ##Camilo Ramirez Alarcon   			20142020078
## Codigo
<pre><code>
  """
Método que conviete un número a binarios 
"""
def binario(n):
    if n/2 == 0:
        return n
    else:
        return (n%2) + 10 * binario(n//2)


#print("Ingrese un número decimal")
#print(binario(int(input())))

  
"""
Metodo que retorna el modulo de dos valores
"""
def mod(a,b):
    if a<b:
        return a
    else:
        return mod(a-b,b)

#print("Ingrese un numero")
#a=int(input())
#print("Ingrese un numero")
#b=int(input())
#print(mod(a,b))
<code>
