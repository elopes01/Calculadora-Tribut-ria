Calculadora-Tribut-ria
First Project

custo=float(input("Digite o valor do custo: "))
imposto=float(input("Digite o valor do imposto do seu país: "))
impostoporcentual=imposto/100
valorfinal=custo+(custo*impostoporcentual)

print('O valor do imposto é: {}'.format(custo*impostoporcentual))
print('O valor total do produto com o imposto é: {}'.format(valorfinal))