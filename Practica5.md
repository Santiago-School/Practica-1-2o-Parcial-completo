print("Santiago Carrasco preguntar los numeros ganadores")

# inicializa una lista vacia para los numeros
numerosloteria = []

# pide al usuario que ingrese los numeros triunfadores
while True:
    numero = input("introduce un numero ganador de la loteria: ")
    if numero.lower() == 'fin':
        break
    else:
        # convierte el numero a entero y se agrega
        numerosloteria.append(int(numero))

# ordena la lista de numeros de menor a mayor
numerosloteria.sort()

#  muestran los numeros en pantalla
print("los numeros ganadores de la loteria son:", numerosloteria)

![image](https://github.com/user-attachments/assets/ee44f402-ca4f-4f16-bad9-bfb847b943ef)
