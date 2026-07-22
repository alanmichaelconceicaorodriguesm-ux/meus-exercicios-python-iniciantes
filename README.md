# meus-exercicios-python-iniciantes
São questões simples para minha pessoa ter uma ser noção do meu progresso. 

salario = float(input("Qual o salário do funcionário? R$"))

if salario <= 1250:
    novo = salario + (salario * 15 / 100)
    
else:
    novo = salario + (salario * 10 / 100)
    
print(f"Quem ganhava R${salario:.2f}, agora está ganhando R${novo:.2f}.")
