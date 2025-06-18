# Dados-do-usu-rio
um código curto com perguntas ao usuário. 
from datetime import datetime

print ('Olá, seja bem vindo! ')

nome = input ('Qual é o seu nome? ')

hora_atual = datetime.now().strftime('%H:%M:%S')

print (f'Seja Bem vindo ao meu programa! {nome}! Horário da inscrição: {hora_atual}. ') 
