# Taller-1
![Logo Sencillo Neón para Bar (1)](https://user-images.githubusercontent.com/124845009/225525190-74a554dd-f187-46ca-bb9d-0b3d7301194a.png)

Dilan Steven Narvaez Pulido

Laura Carolina Lozada Escobar

Ariadne Zindy Tatiana Agreda Sigindioy

# 1. Quizz - Python Beginner Quizz
*Quizz Ariadne Zindy Tatiana Agreda Sigindioy*

![image](https://user-images.githubusercontent.com/124845009/225464718-e4b74a4d-ca0c-417b-b55a-658d0a25f87a.png)

*Quizz Laura Carolina Lozada Escobar*

![WhatsApp Image 2023-03-11 at 1 36 56 AM](https://user-images.githubusercontent.com/124845009/225465367-e337ee61-6158-46ec-9543-8345e0bfc5df.jpeg)

*Quizz Dilan Steven Narvaez Pulido*

![image](https://user-images.githubusercontent.com/124845009/225465375-f17c6ccc-5395-450a-98e1-5a03563a621f.png)

# 2. Programa que lee tres números reales y determina cuál es el mayor.

x: float = float(input("ingrese el primer número: "))

y: float = float(input("ingrese el segundo número: "))

z: float = float(input("ingrese el tercero número: "))

if x > y and x > z:

    print(x)
    
elif y > x and y > z:

    print(y)
    
else:

    print(z)
 
 # Diagrama de flujo
 
 [![diagrama-de-flujo-punto-2.png](https://i.postimg.cc/DfSqV3Lq/diagrama-de-flujo-punto-2.png)](https://postimg.cc/ThXymSkw)
 
 # 3. Programa que lee un números enteros y determina si es par o impar.
 
 x: int = int(input("ingrese un número entero: "))
 
y: int = 2

if x % y == 0:

    print("el número es par")
    
else:

    print("el número es impar")

# Diagrama de flujo 

[![Diagrama-sin-t-tulo-drawio.png](https://i.postimg.cc/GtDWVSbv/Diagrama-sin-t-tulo-drawio.png)](https://postimg.cc/GTcgsK8p)

# 4. Programa que lee dos números reales y determina si el primero es múltiplo del segundo

x: float = float(input("ingrese primer número: "))

y: float = float(input("ingrese segundo número: "))

if x % y == 0 and x % y != 1:

    print("el primer número es múltiplo del segundo")
    
else:

    print("el primer número no es múltiplo del segundo")
    
# 5. Programa que lee tres números reales y determine si la suma de los dos primeros es mayor, menor o igual que el tercer número.

x: float = float(input("ingrese primer número: "))

y: float = float(input("ingrese segundo número: "))

z: float = float(input("ingrese tercer número: "))

if x + y > z:

    print("la suma de los dos primeros números es mayor que el tercer número")
    
elif x + y < z:

    print("la suma de los dos primeros números es menor que el tercer número")
    
else:

    print("la suma de los dos primeros números es igual que el tercer número")
 
Diagrama de flujo 
[![Diagrama-flujo-5.png](https://i.postimg.cc/qqbwTWTz/Diagrama-flujo-5.png)](https://postimg.cc/ZvNpP70S)

# 6. Programa que solicita al usuario una letra y determine si es una vocal o una consonante.

x: str = str(input("ingrese una letra (hacerlo en minúsculas): "))

vocales: str = ["a","e","i","o","u"]

consonantes: str = ["b","c","d","f","g","h","j","k","l","m","n","p","q","r","s","t","v","w","x","y","z"]

if x in vocales:

    print("es una vocal")
    
elif x in consonantes:

    print("es una consonante")
    
else:

    print("no papi, la `ch` y la `ñ` no cuentan porque no quiero")
    
# 7. Programa que pida 5 números reales y calculando las siguientes operaciones:
* El promedio:

a: float = float(input("ingrese primer número: "))

b: float = float(input("ingrese segundo número: "))

c: float = float(input("ingrese tercer número: "))

d: float = float(input("ingrese cuarto número: "))

e: float = float(input("ingrese quinto número: "))

promedio: float = (a+b+c+d+e) // x

x: int = 5

mediana: float = a>b>c>d>e

while (a+b+c+d+e) // x:

    print(promedio)
  
* La mediana

c: float = float(input("ingrese tercer número: "))

d: float = float(input("ingrese cuarto número: "))

e: float = float(input("ingrese quinto número: "))

#Ordenar los numeros en orden ascendente

numeros = [a, b, c, d, e]

numeros_ordenados = sorted (numeros)

print(numeros_ordenados)

#Calcular la mediana

if len(numeros_ordenados) % 2 == 0:

    mediana = (numeros_ordenados[len(numeros_ordenados)//2 - 1] + numeros_ordenados[len(numeros_ordenados)//2]) / 2
    
else:

    mediana = numeros_ordenados[len(numeros_ordenados)//2]
    
print("mediana", mediana)

* El promedio multiplicativo (multilplica todos y luego calcula la raíz de la cantidad de operandos)

#Calcular el promedio multiplicativo

Producto= (a * b * c * d * e)

promedio_multiplicativo = Producto **(1/5)

* Ordenar los números de forma ascendente

#Ordenar los numeros en orden ascendente 

numeros = [a, b, c, d, e]

numeros_ordenados = sorted (numeros)

print(numeros_ordenados)

* Ordenar los números de forma descendente
* 
a: float = float(input("ingrese primer número: "))

b: float = float(input("ingrese segundo número: "))

c: float = float(input("ingrese tercer número: "))

d: float = float(input("ingrese cuarto número: "))

e: float = float(input("ingrese quinto número: "))

#Numeros descendentes

numeros = (a, b, c, d, e)

numeros_ordenados = sorted (numeros, reverse=True)

print (numeros_ordenados)

* La potencia del mayor número elevado al menor número

#Calcular la potencia del mayor número elevado al menor número

mayor = max(numeros_ordenados)

menor = min(numeros_ordenados)

potencia = mayor ** menor

print(f"La potencia del mayor número ({mayor}) elevado al menor número ({menor}) es: {potencia}")

* La raíz cúbica del menor número

#Calcular la raíz cúbica del menor número

raiz_cubica = abs(min(numeros_ordenados)) ** (1/3)

print(f"Raizz cúbica del menor número ({min(numeros_ordenados)}) es: {raiz_cubica}")

# 8. Programa al que se le ingrese la frecuencia de una onda en hz y como salida arroja en que parte del espectro electromagnético se encuentra.

frecuencia = float(input("Ingrese la frecuencia en Hz: "))

if frecuencia < 3e9:

    print("La frecuencia " + str(frecuencia) + " se encuentra en el rango de ondas de radio")
    
elif frecuencia < 3e12:

    print("La frecuencia " + str(frecuencia) + " se encuentra en el rango de microondas")
    
elif frecuencia < 4.3e14:

    print("La frecuencia " + str(frecuencia) + " se encuentra en el rango de luz infrarroja")
    
elif frecuencia < 7.5e14:

    print("La frecuencia " + str(frecuencia) + " se encuentra en el rango de luz visible")
    
elif frecuencia < 3e17:

    print("La frecuencia " + str(frecuencia) + " se encuentra en el rango de luz ultravioleta")
    
elif frecuencia < 3e19:

    print("La frecuencia " + str(frecuencia) + " se encuentra en el rango de rayos X")
    
else:

    print("La frecuencia " + str(frecuencia) + " se encuentra en el rango de rayos gamma")

# 9. Programa que recibe el nombre en minúsculas de un país de America y retorna la ciudad capital, si el país no pertenece al continente arroja país no identificado.

print ("¿TE SABES LAS CAPITALES DE LOS PAISES DEL CONTINENTE AMERICANO?")

#programa que reciba el nombre en minúsculas de un país de America y retorne la ciudad capital, si el país no pertenece al continente debe arrojar país no identificado.

#CONTINENTE_AMERICANO

keys= ("Nombre de paises del continente americano")

values= ("Nombre de las capitales correspondientes a los paises del continente americano")

#Lista de paises del continente americano
keys: str = {"Antigua y Barduda", "Argentina", "Bahamas", "Barbados", "Belice", "Bolivia", "Brasil", "Canadá", "Chile", "Colombia", "Costa Rica", "Cuba" "Dominica", "Ecuador", "El Salvador", "Estados Unidos", "Granada", "Guatemala", "Guyana", "Haití", "Honduras", "Jamaica","México", "Nicaragua", "Panamá", "Paraguay", "Perú", "República Dominicana", "San Cristóbal y Nieves", "San Vicente y las Grandinas", "Santa Lucía","Surinam", "Trinidad y Tobago", "Ururguay", "Venezuela"}

#Lista de capitales correspondientes a los paises del continente americano

values: str = {"Saint John", "Buenos Aires", "Nasáu", "Bridgetown", "Belmopán", "Sucre", "Brasilia", "Otawwa", "Santiago de Chile", "Bogotá", "San José", "La Habana", "Roseau", "Quito", "San Salvador", "Washingtón DC", "Saint George", "Ciudad de Guatemala", "Georgetown", "Puerto Príncipe", "Teguciglapa", "Kingston", "México DF", "Managua", "Panamá", "Asunción","Lima", "Santo Domingo", "Basseterre", "Kingstown", "Castries" "Parabarimo", "Puerto España", "Montevideo", "Caracas"}

diccionario = {"Antigua y Barduda":"Saint John","Argentina":"Buenos Aires","Bahamas":"Nasáu","Barbados":"Bridgetown","Belice":"Belmopán","Bolivia":"Sucre","Brasil":"Brasilia","Canadá":"Otawwa","Chile":"Santiago de Chile","Colombia":"Bogotá","Costa Rica":"San José","Cuba":"La Habana","Dominica":"Roseau","Ecuador":"Quito","El Salvador":"San Salvador","Estados Unidos":"Washingtón DC","Granada":"Saint George","Guatemala":"Ciudad de Guatemala","Guyana":"Georgetown","Haití":"Puerto Príncipe","Honduras":"Teguciglapa","Jamaica":"Kingston","México":"México DF","Nicaragua":"Managua","Panamá":"Panamá","Paraguay":"Asunción","Perú":"Lima","República Dominicana":"Santo Domingo","San Cristóbal y Nieves":"Basseterre","San Vicente y las Grandinas":"Kingstown","Santa Lucía":"Castries","Surinam":"Parabarimo","Trinidad y Tobago":"Puerto España","Ururguay":"Montevideo","Venezuela":"Caracas"}

print ("¡¡Recuerda: Los nombres propios inician con mayúscula!!")

x: str = str(input("Ingrese correctamente escrito (con tildes) el nombre del país que desea consultar (hacerlo en minúsculas): "))

if x in keys:

    print (diccionario.get(x))
    
else:

    print ("País no identificado. No pertenece al contiente americano")

# 10. Programa que dada una distancia calcula:

* El tiempo que le tomaría a la luz recorrer la distancia.

* El tiempo que le tomaría al sonido (en el aire) recorrer la distancia.

* El tiempo que le tomaría al vehiculo comercial más veloz recorrer la distancia.

* El tiempo que le tomaría a Bolt recorrer la distancia.

#Escriba un programa que dada una distancia calcule:

print ("QUIÉN SERÁ MÁS VELOZ? ")

vl : float = 299.792458 #Velocidad de la Luz (km/s)

s : float = 340 # Velocidad del Sonido [m/s]

st : float = 508.73 # Velocidad del SSC TUATARA [km/h]

b : float = 42 # Velocidad Usain Bolt [km/h]

d : float = float # Distancia ingresada a consultar

t: float = float # Tiempo respuesta

m: int = 1000 # metros equivalen a un kilometro

g: int = 3600 # segundos equivalen a una hora

d: float = float(input("Ingrese en metros la distancia a consultar, sin agregar el factor de conversión (m)):"))

#1. Velocidad de la luz

print ("¿LA LUZ? (La velocidad de la luz es de 299.792,459 km/s)")

t = d / vl / m

print(t, "m/s")

#2. Velocidad del sonido

print ("¿EL SONIDO? (La onda de sonido en promedio es de 340 m/s)")

t = d / s

print(t, "m/s")

#3. Velocidad del auto comercial SSC TUATARA

print ("¿EL SSC TUATARA? (El automóvil comercial más veloz del mundo que alcanza los 508,73 km/h)")

t = d / st / m / g

print(t, "m/s")

#4. Velocidad del Usain Bolt

print ("¿O USAIN BOLT? (Ex atleta profesional jamaiquino, quien puede correr a 42 km/h)")

t = d / b / m / g

print(t, "m/s")
