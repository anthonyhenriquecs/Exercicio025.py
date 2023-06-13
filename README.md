# Exercicio025.py
#Crie um programa que leia o nome de uma pessoa e diga se ela tem “SILVA” no nome.

n = str(input('Qual seu nome: ')).strip()
print('seu nome tem Silva? {}'.format('silva' in n.lower()))
