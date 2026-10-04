# Lê a linha de entrada e divide os valores pelos espaços
entrada = input().split()

# Atribui cada valor à sua respectiva variável
projeto = entrada[0]
solicitados = int(entrada[1])
limite = int(entrada[2])

# Regra 1: Verifica se algum dos números é negativo
if solicitados < 0 or limite < 0:
    print("INVALID")

# Regra 2: Se a quantidade solicitada for menor ou igual ao limite
elif solicitados <= limite:
    print("APPROVED")

# Regra 3: Se a quantidade solicitada for maior que o limite
else:
    print("REJECTED")
