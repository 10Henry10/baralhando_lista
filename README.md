# baralhando_lista
Programa que cria uma lista e baralha a ordem

import random

print('Mostrar a  Ordem de Escolha\n')

n1 = str(input('Digite o nome do Primeiro Aluno: '))
n2 = str(input('Digite o nome do Segundo Aluno: '))
n3 = str(input('Digite o nome do Terceiro Aluno: '))
n4 = str(input('Digite o nome do Quarto Aluno: '))

lista = [n1, n2, n3, n4]
random.shuffle(lista) #significado de shuffle é baralhar

print('\/\/ A ordem de apresentação escolhida foi \/\/\n')
print(lista)
