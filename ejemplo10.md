
![image](https://github.com/user-attachments/assets/27fce62a-eec6-42c6-ad15-ad43fdfd97d2)

def es_bisiesto(anio):
    if (anio % 4 == 0 and anio % 100 != 0) or (anio % 400 == 0):
        return True
    else:
        return False

# Ejemplos de uso
print(es_bisiesto(2024))  # Debería devolver True
print(es_bisiesto(1900))  # Debería devolver False
print(es_bisiesto(2000))  # Debería devolver True
print(es_bisiesto(2023))  # Debería devolver False
