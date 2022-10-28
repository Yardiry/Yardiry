str= 'Manzana Verde para el batido'

start = 'Verde'
end = 'batido'

result = str[str.find(start)+len(start):str.rfind(end)]
print(result)
