![image](https://github.com/user-attachments/assets/d371f92f-3fcd-4100-befc-fb19e6324482)

# Solicitar el año en curso al usuario
anio_en_curso = int(input("Ingrese el año en curso: "))

# Función para calcular la edad
def calcular_edad(anio_nacimiento, anio_actual):
    return anio_actual - anio_nacimiento

# Lista para almacenar los datos de las personas
personas = []

# Solicitar los datos de tres personas
for i in range(3):
    nombre = input(f"Ingrese el nombre de la persona {i + 1}: ")
    anio_nacimiento = int(input(f"Ingrese el año de nacimiento de {nombre}: "))
    edad = calcular_edad(anio_nacimiento, anio_en_curso)
    personas.append((nombre, edad))

# Imprimir las edades
for nombre, edad in personas:
    print(f"{nombre} cumplirá {edad} años durante el año en curso.")

# Ejemplo de uso:
# Si el usuario ingresa el año en curso como 2024,
# y las personas son:
# - "Carlos", nacido en 2000
# - "Ana", nacida en 1995
# - "Luis", nacido en 2010
# La salida sería:
# Carlos cumplirá 24 años durante el año en curso.
# Ana cumplirá 29 años durante el año en curso.
# Luis cumplirá 14 años durante el año en curso.
