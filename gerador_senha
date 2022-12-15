import random

caracteres = ['@','!','-','_','/','a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z', '1', '2', '3', '4', '5', '6', '7', '8', '9', '0']
senha = ""

print("Digite a quantidade de caracteres desejado: ")
num = int(input("Tamanho da senha"))

def gerar_senha(n):
    global senha
    if n<=0:
        return(senha)
    else:
        senha += (random.choice(caracteres))
        return(gerar_senha(n-1))

print(gerar_senha(num))
