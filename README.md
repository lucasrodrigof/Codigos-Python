# Programações
 Pasta com programações em Python
#Lista de Exericios 3
#Nome: Lucas Rodrigo Leite Fonseca Moreira
#RA:1460482111036

#1
nota = float (input('Insira uma nota entre zero e dez: '))
while nota<0 or nota>10:
    print('Nota entre 0 e 10: ')
    nota = float (input('Insira uma nota entre zero e dez: '))
print (('A nota é: '), nota)

#2
login = input('Digite seu usuário: ')
senha = input('Digite sua senha: ')
while login == senha:
    print('Sua senha deve ser diferente do usuário')
    login = input('Digite seu usuário: ')
    senha = input('Digite sua senha: ')

#3
a = 80000
b = 200000
anos = 0
while a < b:
    a = a + a * 0.03
    b = b + b * 1.5/100
    anos = anos + 1
print (anos)

#4
n = int (input('Insira um valor: '))
a, b = 1, 1
cont = 1
while cont <= n-2:
    a, b = b, a + b
    cont = cont + 1

print (f'Fibonacci({n}) = {b}')

#5
a = int(input("Digite um valor: "))
b = int(input("Digite outro valor: "))
 
while a % b != 0:
 a, b = b, a%b
 
print(f"O mdc de seu número é: {b}")