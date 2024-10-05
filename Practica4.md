print("Santiago Carrasco: Solicitar calificacion por cada materia y mostrarla")

# se mete en la lista las materias
materias = ["Ingles","matematicas","python", "ecosistemas", "humanidades"]
calificaciones = []

# la lista de materias y se solicita la calificacion para cada una
for materia in materias:
    calificacion = input(f"introduce la calificacion para {materia}: ")
    calificaciones.append(calificacion)
# Se almacena la calificacion en la lista

# Se muestran las calificaciones en pantalla
for materia, calificacion in zip(materias, calificaciones):
    print(f"En {materia} has obtenido {calificacion}")


![image](https://github.com/user-attachments/assets/3bebe202-5acb-47a4-b223-e87aa4348d8f)
