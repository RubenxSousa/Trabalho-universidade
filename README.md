print("Bem-vindo ao App de Vendas da Empresa Sousa's Corp!")
print("Desenvolvido por Antonio Rubens Sousa\n") 

valor_unitario = float(input("Digite o valor unitário do produto: "))
quantidade = int(input("Digite a quantidade vendida: "))

valor_total = valor_unitario * quantidade

if valor_total < 2500:
    desconto = 0
elif 2500 <= valor_total < 6000:
    desconto = 4
elif 6000 <= valor_total < 10000:
    desconto = 7
else:  
    desconto = 11

valor_desconto = valor_total * (1 - desconto/100)

print(f"\nValor total SEM desconto: R$ {valor_total:.2f}")
print(f"Desconto aplicado: {desconto}%")
print(f"Valor total COM desconto: R$ {valor_desconto:.2f}")
# Trabalho-universidade
