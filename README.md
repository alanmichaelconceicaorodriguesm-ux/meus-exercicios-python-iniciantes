# meus-exercicios-python-iniciantes
São questões simples para minha pessoa ter uma ser noção do meu progresso. 

matriz = [
[1, 2, 3, 4],
[5, 6, 7, 8],
[9, 10, 11, 12]
] # Variável.


# Bloco 1.
print("Todos os elementos da primeira linha:")

for elem in matriz[0]:
	print(elem, end=" ")
print()
		
print("—" * 20)


# Bloco 2.
print("Todos os elementos das colunas e linhas:\033[0;34;47m")

for linha in matriz:
	for elem in linha:
		print(elem, end=" ")
	print()

print("\033[m" + "—" * 20)

# Outros comandos. Continua...


# Bloco 3.

bloco = int(input('''Digite um número caso deseje uma linha em específico. Os números estão logo abaixo:\n1 - Para a primeira linha.\n2 - Para a segunda linha.\n3 - Para terceira linha.\nDigite um número: '''))

# Bloco 4.

# Primeira condição.
if bloco == 1:
    print(f"Todos os elementos da primeira linha: ")
    for elem in matriz[0]:
        print(elem, end=" ")

# Segunda condição.            
elif bloco == 2:
    print(f"Todos os elementos da segunda linha: ")
    for elem in matriz[1]:
        print(elem, end=" ")
        
# Terceira condição.   
elif bloco == 3:
    print(f"Todos os elementos da terceira linha: ")
    for elem in matriz[-1]:
        print(elem, end=" ")
 
# Caso nemhuma condição for atendida. Termina aqui.    
else:
    print("Número Inválido.")
print()
        
# Outros comandos. Continua...
