# 1.1 - Pedir o nome do aluno
nome = input("Digite o nome do aluno: ")

# 1.2 - Solicitar 4 notas
nota1 = float(input("Digite a 1ª nota: "))
nota2 = float(input("Digite a 2ª nota: "))
nota3 = float(input("Digite a 3ª nota: "))
nota4 = float(input("Digite a 4ª nota: "))

# 1.3 - Calcular a média anual
media = (nota1 + nota2 + nota3 + nota4) / 4

# 1.4 - Exibir a média final
print(f"\nAluno: {nome}")
print(f"Média final: {media:.2f}")

# 1.5 - Informar situação
if media >= 70:
    print("Situação: Aprovado")
else:
    print("Situação: Reprovado")
