nome = input ("Digite o nome do funcionário: ")
print ("Nome do funcionário é", nome, "\n")

idade = int(input("Idade do funcionário: "))
print ("A idade do funcionario é:", idade,"anos, sendo assim", nome,", ele nasceu em", (2023 - idade),"!\n")

#dessa forma abaixo, ele não bloqueará a escrita de string, mas ele irá validar e interromperá o processo se for string
#idade = input ("Digite sua idade:")
#idade == int(idade)
#print ("Sua idade é:", idade)

#print (nome,", você nasceu em", (2023 - idade),"!")

saldo = float(input("Qual o atual salário do funcionário? "))
perc = float(input("Qual o percentual de aumento para o funcionário? \n"))
saldoatual = ((saldo*perc)/100+saldo)
#perc = ((saldo*30)/100+saldo))

print ("O salario do funcionário é:", saldo, ", e o seu Salário com aumento é:", saldoatual, "\n")

print (f"Você {nome} que nasceu em {2023 - idade} terá um aumento de {perc}%, que terá um de R${saldo + perc}")