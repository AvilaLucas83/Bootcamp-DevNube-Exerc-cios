Inteiro n

inserir valor n

função fibonacci(n)
  se n < 0
    retorne "Não é possível número negativo"
   fimse

  se n == 0
    retorne "posição 0 da sequência"
  fimse

  se n == 1
    retorne "posição 1 da sequência"
  fimse

  se n > 1
    então n = (n - 1) + (n - 2)
    retorne "posição " + n "da seqência"
  fimse

fim função fibonacci
