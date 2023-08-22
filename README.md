# bocky
def inicio():
  print("Bienvenido a Bocky  ")
  print('''
               _                  __
    ____ ___  (_)  ________  ____/ /
   / __  __ \/ /  / ___/ _ \/ __  /
  / / / / / / /  / /  /  __/ /_/ /
 /_/ /_/ /_/_/  /_/   \___/\____/''')

def datos():
  nombre = input("Para empezar, dime como te llamas. ")
  anno_nacimi= int(input("escribe tu año de nacimiento "))
  edad= 2023-anno_nacimi
  return (nombre,edad)

def saludar(nom1, edad1):
   print(f"hola {nom1} tienes {edad1} años")

### Acá comienza el programa
inicio()
datos()
(nom1, edad1)=datos()
saludar()
nombre= input("ingrese su nombre:")
edad= input("ingrese su fecha de nacimiento:")
genero= input("ingrese su genero:")
estatura= input("ingrese su estaura en metros")

print("Hola ", nombre(), ", bienvenido a Mi Red")
print(saludar)
print("Muy bien.Entonces podemos crear un perfil con estos datos.")
print(nombre)
print(edad)
print(genero)
print(estatura)
print("--------------------------------------------------")
print("Gracias por la información.Esperamos que disfrutes con Mi Red")
mensaje = input("Ahora vamos a publicar tu primer mensaje. Que piensas hoy? ")
print(mensaje)
print("--------------------------------------------------")
print("Gracias por usar Mi Red. ¡Hasta pronto!")
continuar = True
while continuar:
    escribir_mensaje = str(input("¿Deseas escribir un mensaje? (S/N) "))
    if escribir_mensaje == "S" or escribir_mensaje == "s" or escribir_mensaje == "" :
        mensaje = input("Vamos a publicar un mensaje. ¿Qué piensas hoy? ")
        print()
        print("--------------------------------------------------")
    else:
      if escribir_mensaje == "N" or escribir_mensaje == "n" or escribir_mensaje == "" :
        continuar = False
        print("--------------------------------------------------")
        print(nombre, "dice:", mensaje)
        print("--------------------------------------------------")
    nombre= str(input("¡DESEA MODIFICAR EL NOMBRE DE USUARIO?(S/N)"))
if nombre == "S" or nombre == "s" or nombre== "":
    nuevo_nombre=input("Cual es su nuevo nombre:")
    nombre=nuevo_nombre
    print("persona modificada")
else:
   nombre=="n"
   continuar= False

   # Cantidad de amigos
num_amigos = int(input("Muy bien. Finalmente, cuéntame cuantos amigos tienes. "))

#Con los datos recolectados escribimos en pantalla un texto que resuma los datos que hemos obtenido
print()
print("Muy bien,", nombre, ". Entonces podemos crear un perfil con estos datos.")
print("--------------------------------------------------")
print("Nombre:  ", nombre)
print("Edad:    ", edad, "años")
print("Estatura:", estatura_m, "metros y", estatura_cm, "centí­metros")
print("Amigos:  ", num_amigos)
print("sexo:   ", sexo)
print("Pais de nacimiento.   ",pais_nacimiento)
print("--------------------------------------------------")
print("Gracias por la información. Esperamos que disfrutes con Mi Red")
print()

#Usaremos una variable bool para indicar si el usuario desea continuar utilizando 
# el programa o no
continuar = True

while continuar:

 escribir_mensaje = str (input ("¿Deseas escribir un mensaje? (Si/No) ")) 

if escribir_mensaje == "Si" or escribir_mensaje == "si" or escribir_mensaje == "s" or escribir_mensaje == "sI" or escribir_mensaje == "":
   print()
   mensaje = input("Expresa tu mensaje ")
   print()
   print("-----------------------------------------------------------------")
   print(nombre, "dice:", mensaje)
   print("-----------------------------------------------------------------")

elif escribir_mensaje == "No" or escribir_mensaje == "no" or escribir_mensaje ==  "n" or escribir_mensaje == "nO" or escribir_mensaje =="NO" or escribir_mensaje == "":
   continuar = False
else:
   print ("Opción no válida")

print()
print("Gracias por usar BOCKY. ¡Hasta la proxima!")

