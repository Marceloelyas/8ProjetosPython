import random as rd
from random import sample
import numpy as np
import re
import getpass
import pwinput

print('-' * 50)
print('                  MEGA SENA        ')
print('-' * 50)

nome = str(input('Para iniciar, Qual é a seu nome: ')).upper()
print(f'(Boa Sorte {nome}!!! \n Mas antes temos que confirmar su idade?\n)

def verificar_idade(idade):
    if idade >= 18:
        return "OK, pode seguir em Frente"
    else:
        print('Desculpe, você não tem idade suficiente para jogar. Tente novamente.\n')

while true:
    nome = str(input('Para iniciar, Qual é a seu nome: ')).upper()
    print(f'(Boa Sorte {nome}!!! \n Mas antes temos que confirmar su idade?\n)

    idade_jogador = int(input("Digite sua idade idade: "))
    resultado = verificar_idade(idade_jogador)

    if resultado == "OK, pode seguir em Frente":
        # Continuar com o restante do código da Mega Sena
        break
    else:
        print("Desculpe, você não tem idade suficiente para jogar. Tente novamente.\n')
