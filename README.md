# Sequencia-de-Fibonacci
# Teste para Target Sistemas
def verificando_fibonacci(numero):
  a, b = 0, 1
  while b < numero:
      a, b = b, a + b
  if b == numero:
      return True
  else:
      return False

numero = int(input("Informe um número para testar se pertence à sequência de Fibonacci: "))

if verificando_fibonacci(numero):
  print(f"O número {numero} pertence à sequência de Fibonacci.")
else:
  print(f"O número {numero} não pertence à sequência de Fibonacci.")