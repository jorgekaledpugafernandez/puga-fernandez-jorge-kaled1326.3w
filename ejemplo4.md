
![image](https://github.com/user-attachments/assets/93482bd0-52b2-4cb0-a5a8-c78cccafcf5e)

# Solicitar al usuario que ingrese una cadena
cadena = input("Por favor, ingresa una cadena: ")

# Inicializar contador de mayúsculas
contador_mayusculas = 0

# Recorrer cada carácter de la cadena
for caracter in cadena:
    # Comprobar si el carácter es una letra mayúscula
    if caracter.isupper():
        contador_mayusculas += 1

# Mostrar el resultado
print(f"La cadena tiene {contador_mayusculas} letras mayúsculas.")

