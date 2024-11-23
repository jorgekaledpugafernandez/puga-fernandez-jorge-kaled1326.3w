
![image](https://github.com/user-attachments/assets/9c975b37-6453-4967-b9d5-099dc9787114)

def mas_larga(palabras):
    # Inicializar con la primera palabra de la lista
    palabra_mas_larga = palabras[0]
    # Recorrer la lista de palabras
    for palabra in palabras:
        # Comparar la longitud de cada palabra con la longitud de la palabra más larga actual
        if len(palabra) > len(palabra_mas_larga):
            palabra_mas_larga = palabra
    return palabra_mas_larga

# Ejemplo de uso
lista_palabras = ["hola", "mundo", "extraordinario", "python", "función"]
resultado = mas_larga(lista_palabras)
print(f"La palabra más larga en la lista {lista_palabras} es '{resultado}'.")
cl
