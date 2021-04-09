# Calculadora
print('Calculadora de Numéros Inteiros')
print('ººººººººººººººººººººººººººººººººº')
print('Escolha uma das opções Abaixo:')
print('1 - Soma')
print('2 - Subtração')
print('3 - Multiplicação')
print('4 - Divisão')
print('ººººººººººººººººººººººººººººººººº')
num = int(input('Digite a sua opção ex: (1): '))
if num  == 1:
 print('Digite os Numeros que Deseja Somar:')
 n1 = int(input('Primeiro Numero:'))
 n2 = int(input('Segundo Numero:'))
 Rs = n1 + n2
 print('o Resultado da Soma é:',Rs)
elif num == 2:
  print('Digite os Numeros que deseja Subtrair de modo que o Segundo sera Subtraido do Primeiro.:')
  n3 = int(input('Primeiro Numero:'))
  n4 = int(input('Segundo Numero:'))
  Rst = n3 - n4
  print('o Resultado da Subtração é:', Rst)
elif num == 3:
    print('Digite os Numeros que Deseja Multiplicar:')
    n5 = int(input('Primeiro Numero:'))
    n6 = int(input('Segundo Numero:'))
    Rm = n5 * n6
    print('o Resultado da Multiplicaçao é:', Rm)
elif num == 4:
    print('Digite os Numeros que Deseja Dividir  de modo que o Primeiro sera o Dividendo e o Segundo sera o Divisor:')
    n7 = int(input('Primeiro Numero:'))
    n8 = int(input('Segundo Numero:'))
    Rd = n7 / n8
    print(f'o Resultado da Divisao é:{Rd:.2f}')
else:
  print('Opção invalida')
print('ººººººººººººººººººººººººººººººººº')
