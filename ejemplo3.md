
def filtrar_palabras(palabras, n):
    # Crear una lista vacía para almacenar las palabras que cumplen la condición
    palabras_filtradas = []
    # Recorrer cada palabra en la lista de entrada
    for palabra in palabras:
        # Comprobar si la longitud de la palabra es mayor que n
        if len(palabra) > n:
            # Añadir la palabra a la lista filtrada
            palabras_filtradas.append(palabra)
    return palabras_filtradas

# Ejemplo de uso
lista_palabras = ["hola", "mundo", "extraordinario", "python", "función"]
n = 5
resultado = filtrar_palabras(lista_palabras, n)
print(f"Las palabras en la lista {lista_palabras} que tienen más de {n} caracteres son: {resultado}.")

![image](https://github.com/user-attachments/assets/f36b8444-f1bb-4d76-bd19-dbd00ea1a25e)
