# Temperatura-Carne
Código python para descobrir o ponto da carne do cliente

temp_cel =int(input('Qual a temperatura da carne'))

if temp_cel < 48:
  print('Precisa cozinhar por mais tempo')

elif temp_cel in range(48, 53):
  print('Selada')

elif temp_cel in range(54, 59):
    print('Ao ponto para o mal')

elif temp_cel in range(60, 64):
   print('Ao ponto')

elif temp_cel in range(65, 70):
    print('Ao ponto para o bem')

elif temp_cel >=71:
    print('bem passada')
