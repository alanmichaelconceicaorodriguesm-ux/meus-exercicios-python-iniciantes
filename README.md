# meus-exercicios-python-iniciantes - 10
São questões simples para minha pessoa ter uma ser noção do meu progresso. 

# Variável.
matriz = [
[1, 2, 3, 4],
[5, 6, 7, 8],
[9, 10, 11, 12]
]


# Bloco 1.
print("Todos os elementos da primeira linha:", "\033[0;31m")

# Mostrar Apenas a Primeira Linha.
for elem in matriz[0]:
	print(elem, end=" ")
print()
		
print("\033[0;31m", "–" * 20, "\033[m")

# Bloco 2.
print("Todos os elementos das colunas e linhas:", "\033[0;31m",)

# Mostrar a Matriz por Completo.
for linha in matriz:
	for elem in linha:
		print(elem, end=" ")
	print()

print("\033[m" ,"\033[0;31m", "–" * 20, "\033[m")

# Continuação do Programa...

#___________________________________

# Bloco 3.
bloco = int(input('''Digite um número caso deseje uma linha em específico. Os números estão logo abaixo:\n1 - Para a primeira linha.\n2 - Para a segunda linha.\n3 - Para terceira linha.\nDigite um número: '''))

# Bloco 4.

# Primeira Condição.
if bloco == 1:
    print(f"Todos os elementos da primeira linha: ", "\033[0;31m")
    for elem in matriz[0]:
        print(elem, end=" ")

# Segunda Condição.            
elif bloco == 2:
    print(f"Todos os elementos da segunda linha: ", "\033[0;31m")
    for elem in matriz[1]:
        print(elem, end=" ")
        
# Terceira Condição.   
elif bloco == 3:
    print(f"Todos os elementos da terceira linha: ")
    for elem in matriz[2]:
        print(f"\033[0;31m{elem}\033[m", end=" ")
         
# Caso Nemhuma Condição for Atendida. Termina Aqui.    
else:
    print("\033[0;31m", "Número Inválido.", "\033[m")
print()
 
print("\033[0;31m", "-" * 20, "\033[m")        
# Próximo Bloco de Comando...

#___________________________________

# Teste de Comandos...

# Bloco 5.
coluna = float(input('''Digite um número de 1 a 4 para a coluna de sua escolha:\n1 - Para a primeira coluna.\n2 - Para a segunda coluna.\n3 - Para a terceira coluna.\n4 - Para a quarta coluna.\nDigite um número: '''))

# Primeira Condição.
if coluna == 1:
    print(f"Todos o elementos da da primeira coluna: \033[0;31m{matriz[0][0]}, {matriz[1][0]} e {matriz[2][0]}\033[m.") 

# Segunda Condição.        
elif coluna == 2:
    print(f"Todos os elementos da segunda coluna: \033[0;31m{matriz[0][1]}, {matriz[1][1]} e {matriz[2][1]}\033[m.")

# Terceira Condição.
elif coluna == 3:
    print(f"Todos os elementos da terceira coluna: \033[0;31m{matriz[0][2]}, {matriz[1][2]} e {matriz[2][2]}\033[m.")
    
# Quarta Condição.
elif coluna == 4:
    print(f"Todos os elementos da quarta coluna: \033[0;31m{matriz[0][3]}, {matriz[1][3]} e {matriz[2][3]}\033[m.")

# Última Condição
else:
    print("\033[0;31m", "Número Inválido.", "\033[m")
    
print("\033[0;31m", "—" * 20, "\033[m")    

print("\033[0;34m", "Completo.", "\033[m")

print("\033[0;31m", "–" * 25, "\033[m", "Fim", "\033[0;31m", "–" * 25, "\033[m")    
print()

# Completo.
