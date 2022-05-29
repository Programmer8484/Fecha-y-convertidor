# Fecha-y-convertidor
# Un programa que muestra la fecha y un convertidor de unidades.

# Crea un programa que muestre la fecha.
from datetime import date
date.today()
print(f"Today's date is:{date.today()}")

# Construir un convertidor de unidades.
parsec = 11
lightyears = 3.26156 * parsec
print(f"{str(parsec)} parsec is: {str(lightyears)} lightyears. ")
