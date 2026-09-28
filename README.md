# meus-exercicios-python-iniciantes - 10
São questões simples para minha pessoa ter uma ser noção do meu progresso. 

from datetime import date

ano = int(input("Qual ano você quer analisar ou digite 0 para o ano atual:  "))

if ano == 0:
    ano = date.today().year
    print(f"Seu ano atual é: {ano}")

if ano % 4 == 0 and ano % 100 != 0 or 400 == 0:
    print(f"Bissexto: {ano}")
 
else:
    print(f"Não é Bissexto: {ano}")
    
