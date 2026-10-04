# Desafio de Projeto - DIO

### Resolução em Python

```python
# Lê a linha de entrada e divide os valores pelos espaços
entrada = input().split()

# Atribui cada valor à sua respectiva variável
projeto = entrada[0]
solicitados = int(entrada[1])
limite = int(entrada[2])

# Regra 1: Verifica se a quantidade solicitada ultrapassa o limite permitido
if solicitados > limite:
    print(f"Projeto {projeto}: Quantidade solicitada excede o limite.")
else:
    print(f"Projeto {projeto}: Aprovado.")
