1) Faça um programa que peça as 4 melhores notas de atividades contínuas, calcule e mostre
a média.

n1 = int (input('Digite a primeira nota:'))
n2 = int (input('Digite a segunda nota:'))
n3 = int (input('Digite a terceira nota:'))
n4 = int (input('Digite a quarta nota:'))
media = (n1+n2+n3+n4)/4
print (' Sua média é:', media)


2) Faça um programa que converta metros para milímetros.

n = float (input (' Insira o número em metros:'))
n1 = n*1000
print ( ' A Conversão para milímetros é:',n1)

3) Faça um programa que peça o raio de um círculo, calcule e mostre sua área.

r = float (input ( ' Qual o raio do círculo:'))
pi = 3.14
a = pi * (r*r)
print ('A área  do circulo é:', a,'m2')

4) Faça um programa que peça o valor do lado de um quadrado, calcule a área e em seguida
exiba o dobro deste valor para o usuário.

v = int (input ( ' Qual o valor de um lado do quadrado:'))
a = int (v * v)
d = int (a * 2)
print (' O dobro da área é:', d, 'm2')

5) Faça um programa que pergunte a diária do aluguel de um carro e quantos dias irá durar a
locação, calcule o valor final do aluguel e exiba o resultado na tela.

a = float (input ('Qual o valor da diária do carro:'))
d = int ( input (' Quantos dias irá durar a locação:'))
f = a*d
print (' O valor final do aluguel do carro é:',f)



