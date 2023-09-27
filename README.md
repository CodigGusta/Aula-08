# Aula-08
# # # my_tuple = (1,3,645,89,76,45)
# # # indice = my_tuple[2]
# # # print(indice)




# # # my_tuple2 = (20,30,60,15,15)
# # # my_tuple = my_tuple2
# # # print(my_tuple)



# # # tuple1 = (1,5,8,78,9,64)
# # # print(tuple1)

# # # transform = list(tuple1)
# # # print(transform)


# # # vogais = ('a','b',"e",'r','i')
# # # for letras in vogais:
# # #     print(letras)


# # regiao = ['cataratas', 'amazonia']
# # s,n = regiao
# # print('regiao sul:', s)
# # print('regiao norte:',n)




# # 1 -  Crie uma tupla chamada `frutas` com pelo menos 5 frutas diferentes. Em seguida, acesse e imprima o terceiro elemento da tupla. 
# frutas = ('maca','uva','banana','melao','jabuticaba')

# print(frutas[2])

# 2 - Crie uma tupla chamada `numeros` com alguns números inteiros. Em seguida, converta essa tupla em uma lista e imprima a lista resultante.
# numeros = (1,22,15,2,36,66)
# trans = list(numeros)
# # 3 - Crie uma tupla chamada `meses` com os nomes dos meses do ano até Setembro. Use um loop `for` para imprimir cada mês em uma linha separada.
# meses = ('janeiro','fevereiro','marco','abril','maio','junho','julho')
# for i in meses:
#     print(i)
# # 4 - Crie uma lista chamada `notas` com algumas notas de alunos. Em seguida, converta essa lista em uma tupla e imprima a tupla resultante.

# notas = [20,36,2,1,36,25]

# lista = tuple(notas)
# print(lista)


# 5 - Crie uma lista chamada `ponto` que represente as coordenadas (x, y) de um ponto. Em seguida, 
# desempacote os elementos da lista em duas variáveis separadas (x e y) e imprima os valores.

# ponto = [-55,65]
# x,y = ponto
# print(f'cordenada X: {x}')
# print(f'cordenada Y: {y}')




#funcão é uma ação no codigo

# def nome():

# def soma ():
#     t = 15
#     r = 10
#     print( t + r)
# soma()



# def cumprimento():
#     nome = input('Digite seu nome')
#     idade = input('Digite sua idade')
#     print(f"nome do usuario é {nome}a idade é{idade}")

# cumprimento()
 

# def subtracao():
#     c1 = int(input('Digite um numero '))
#     d1 = int(input('Digite outro numero '))
#     print(c1 - d1)

 
# subtracao()



# def calculadora():
#     a = int(input('n1'))
#     b = int(input('n2'))
#     somaN = int(a+b)
#     subN = int(a-b)
#     divN = int(a/b)
#     multN =  int(a*b)

#     print(f'a soma desses numeros é -> {somaN}')
#     print(f'a soma desses numeros é -> {subN}')
#     print(f'a soma desses numeros é -> {divN}')
#     print(f'a soma desses numeros é -> {multN}')


# calculadora()


 #DESAFIO CALCULADORA


# print('SOMA, SUBTRACAO, MULTIPLICACAO, DIVISAO')

# oper = input('Digite a operação ')


# n1 = float(input('N1: '))

# n2 = float(input('N2:'))


# def soma():
#     print('Resulado da soma é ', n1+n2)

# def subtracao():
#     print('Resulado da subtracao é ', n1-n2)


# def multiplicacao():
#     print('Resulado da multiplicacao é ', n1*n2)

# def divisao():
#      print('Resulado da divisao é ', n1/n2)

# if oper == "soma":
#     soma()
# elif oper == "subtracao":
#     subtracao()
# elif oper == "multiplicacao":
#     multiplicacao()
# elif oper == "divisao":
#     divisao()
