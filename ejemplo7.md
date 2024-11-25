
![image](https://github.com/user-attachments/assets/b1ba191c-1826-4109-9b69-faeb5ba3901f)
# Definir una tupla con 10 edades de personas
edades = (15, 22, 30, 18, 25, 19, 21, 34, 27, 13)

# Contar cuántas personas tienen edades superiores a 20
contador = 0
for edad in edades:
    if edad > 20:
        contador += 1

# Imprimir el resultado
print(f"Hay {contador} personas con edades superiores a 20.")
