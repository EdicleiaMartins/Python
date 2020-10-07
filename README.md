# Python
Curso Aula Python
# Bloco de execucao
if __name__ == "__main__":
  print('Hello World...Again') #Mensagem Inicial
  # o simbolo = significa atribuicao(recebe) e o simbolo == significa comparacao
  #var1 = input('Digite um texto:')
  #print('O valor digitado foi:',var1)
  # O valor digitado foi: valor da var1
  print()
  print('Aquisicao de Valores Numericos')
  #  '1' == 1 para converter '1' para 1 int()
  #var2 = int(input('Digite um numero inteiro:'))
  #var3 = int(input('Digite outro numero inteiro:'))
  #var4 = var2 + var3
  #print('A soma dos 2 valores e:', (var2+var3))
  #print('A soma de ',var2,' com ', var3, ' e:', var4)
  #var5 = float(input('Digite outro numero real:'))
  #Exibe com todas as casas decimais
  #print("Var5 = ", var5)
  #Exibe com 2 casas decimais
  #print("Var5 = %.2f" % var5)
  #print("Var5 =", "{:.2f}".format(var5))
  #var6 = "Esse valor foi formatado {:.2f}".format(var5)
  #print("Var6 =", var6)
  var2 = int(input('Digite um numero inteiro:'))
  var3 = int(input('Digite outro numero inteiro:'))
  if var2 > var3:
    print(f"A var2 ({var2}) e maior que a var3 ({var3})")
  # elif --> else if contracao de comandos
  elif var2 == var3:
    print(f"A var2 ({var2}) e var3 ({var3}) sao iguais")
  else:
      print(f"A var2 ({var2}) e menor que a var3 ({var3})")  
  '''
    else:
    if var2 == var3:
      print(f"A var2 ({var2}) e var3 ({var3}) sao iguais")
    else:
      print(f"A var2 ({var2}) e menor que a var3 ({var3})")
  '''



