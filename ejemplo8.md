
![image](https://github.com/user-attachments/assets/246a4400-5238-4d8d-9643-8ca12a7aeac5)
# Definir una lista con un conjunto de nombres
nombres = ["Ana", "Carlos", "Alberto", "Beatriz", "Andrés", "María", "Alejandra", "Pedro", "Antonio", "Lucas"]

# Solicitar al usuario que ingrese la letra a buscar
letra = input("Ingrese la letra que desea buscar: ").lower()

# Contar cuántos nombres comienzan con la letra especificada
contador = 0
for nombre in nombres:
    if nombre.lower().startswith(letra):
        contador += 1

# Imprimir el resultado
print(f"Hay {contador} nombres que comienzan con la letra '{letra}'.")
