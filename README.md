# puga-fernandez-jorge-kaled1326.3w

![image](https://github.com/user-attachments/assets/0ab0b63f-396c-4458-abe4-a8dbe7a9f78f)

def max_in_list(numeros):
    # Inicializamos el máximo con el primer número de la lista
    maximo = numeros[0]
    # Recorremos la lista comparando cada número con el máximo actual
    for numero in numeros:
        if numero > maximo:
            maximo = numero
    return maximo

# Ejemplo de uso
numeros = [1, 2, 3, 9, 4, 5, 6, 7, 8]
resultado = max_in_list(numeros)
print(f"El número más grande en la lista {numeros} es {resultado}.")
