# funcoes-do-python
# Função help:
help(print)

# Função range:
lista = list(range(5))
lista = list(range(1, 6))
lista = list(range(1, 10, 2))
lista = list(range(5, 0, -1))
print (lista)

# Função map
salarios = [1000, 5000, 7000, 850]

def aumentar_salario(salario):
    if salario > 3000:
     novo_salario = salario * 1.07
    else:
       novo_salario = salario * 1.2
    return novo_salario

novos_salarios = list(map(aumentar_salario, salarios))
#novos_salarios = list(map(lambda x: x *1.2, salarios))
print(novos_salarios)

# função filter
salarios = [1000, 5000, 7000, 850]

salarios_altos =list(filter(lambda x: x > 2000, salarios))
print(salarios_altos)

# função sum
custos = [600, 5000, 350, 4000]
custo_total = sum(custos)
custo_total = sum(custos, start=1000)
print(custo_total)

#função sorted
salarios = [9000, 15000, 2000, 5000, 4500]
salarios_ordenados = sorted(salarios)
print(salarios_ordenados)

