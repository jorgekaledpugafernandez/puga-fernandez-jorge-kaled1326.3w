
![image](https://github.com/user-attachments/assets/ac011078-c4a4-4758-bde4-7d33803ecba0)
def contar_vocales(palabra):
    # Convertir la palabra a minúsculas para facilitar la comparación
    palabra = palabra.lower()
    # Inicializar un diccionario para contar las vocales
    conteo = {'a': 0, 'e': 0, 'i': 0, 'o': 0, 'u': 0}
    
    # Contar las vocales en la palabra
    for letra in palabra:
        if letra in conteo:
            conteo[letra] += 1
    
    return conteo

# Ejemplo de uso
palabra = input("Ingrese una palabra: ")
resultado = contar_vocales(palabra)
print(f"El conteo de vocales en la palabra '{palabra}' es: {resultado}.")
