# Algoritmo de multiplicação

- [X] Receber o multiplicando e o multiplicador nos registradores $a0 e $a1
- [X] Retornar o produto nos registradores hi e lo 
- [ ] Inteiro com sinal

## Passo a passo:

1. Armazenar o sinal dos operandos
2. Transformar o numero em positivo
3. Algoritimo 
   1. Resgistrar M(multiplicando) e Q(multiplicador)
   2. Dois registradores -> P[63...32] = 0 e P[31...0] = Q
   3. Se P[0] = 1, P[63...32] = P[63...32] + M (*)
   4. Desloque P à direita
   5. Se nao for a 32 repeticao, volte a *
4.  Se os sinais dos operandos (M e Q) eram diferentes, transformar o produto em negativo
5.  Copiar o conteudo dos dois registradores com para lo e hi