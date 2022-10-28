#Como extraer un texto entre dos caracteres
str= 'Manzana Verde para el batido'

start = 'Verde'
end = 'batido'

resultado = str[str.find(start)+len(start):str.rfind(end)]

print(resultado)
