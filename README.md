peso = float(input('¿Cuál es tu peso?'))
altura = int(input('¿Cuál es tu altura en cm?'))
imc == peso / (altura ** 2)
if 18 <= imc < 25: categoria = "Normal" 
elif 25 <= imc < 30: categoria = "Sobrepeso" 
elif 30 <= imc < 36: categoria = "Obesidad" 
else: categoria = "Fuera del rango definido"

print('indice_masa_corporal = '), categotia, imc
