Código feito na aula de LLP em 2024, código simples em Python:

print(input("Informe seu cargo: "))
print("1-Gerente")
print("2-Analista")
print("3-Estagiário")
print("4-Programador")

escolha=int(input("Digite sua ID: "))
if escolha==1:
    print("Seja bem vindo chefe, você tem acesso ao escritório de Segunda á Quinta")
elif escolha==2:
    print("Seja bem vindo Analista, você tem acesso ao escritório de Terça, Quarta e Sexta")
elif escolha==3:
    print("Seja bem vindo estagiário, você tem acesso ao escritório em dias úteis")
elif escolha==4:
    print("Bem vindo programador, você tem acesso ao escritório de Segunda, Quarta e Sexta")
else:
    print("Você nao trabalha aqui, vaza!")

