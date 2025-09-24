# teste_troco

valor_compra = float(input("Digite o valor da compra (€): "))
valor_pago = float(input("Digite o valor pago pelo cliente (€): "))
troco = (valor_pago - valor_compra)
calcular_troco = (valor_compra, valor_pago)
if valor_pago < valor_compra:
    print(f"Valor pago é insuficiente. Faltam {valor_compra - valor_pago:.2f}€.")
else:
    calcular_troco = valor_compra - valor_pago  
    print(f"Troco a dar: {troco:.2f}€")
