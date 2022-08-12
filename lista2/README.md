# Lista 2

<details>
<summary>Media Ponderada</summary>

[código](mediaponderada.spim)

> Neste exercicio, sua tarefa é ler N números reais com seus respectivos pesos, e calcular a média ponderada entre eles.

## Entrada
- A entrada é composta por diversas linhas. A primeira linha contém um inteiro N (1 < N \leq 10) que determina quantos números estarão envolvidos na média. As 2N linhas seguintes contém: a primeira um número real p_i>0 que determina o peso da i-ésima parcela da média, e a segunda, um número real r_i>0 que representa o i-ésimo valor da média, respectivamente.

## Saída
- Seu programa deve imprimir a média ponderada dos N números lidos. Sua solução deve possuir precisão de, no mínimo, duas casas decimais. Atenção: isso não significa que você deve imprimir exatamente duas casas decimais, mas sim que a diferença entre sua solução e a solução esperada não pode ser maior que 0,01.

## Exemplos

| Entrada | Saida |       
| ------- | ----- |        
| 2       |  4.5  |         
| 0.5     |       |
| 6       |       |
| 0.5     |       |
| 3       |       |

> Dizer que sua solução deve possuir precisão de, no mínimo, duas casas decimais significa dizer que a diferença entre sua solução e a solução esperada deve ser, no máximo, 0.01.

</details>

<details>
<summary>Conversão de temperaturas</summary>

[código](conversaotemp.spim)

> Sabemos que há três escalas de temperatura: Celsius, Fahrenheit e Kelvin. Sua tarefa nesse exercício é realizar a conversão de duas temperaturas em escalas distintas.

## Entrada
- A entrada é composta por três linhas. A primeira e segunda linhas contêm um caracter E (E \in \{ C, F, K \}, denotando Celsius, Fahrenheit e Kelvin, respectivamente) cada. Na primeira linha, o caracter determina em qual escala encontra-se a temperatura, e na segunda, para qual escala você deve converter a temperatura. O caracter da primeira linha sempre será diferente do caracter da segunda. A terceira linha contém um número real T que representa uma temperatura.

## Saída
- Seu programa deve imprimir a temperatura convertida. Sua solução deve possuir precisão de, no mínimo, duas casas decimais.

## Exemplos

| Entrada | Saida |
| ------- | ----- |
| C       |  0.0  |
| K       |       |
| -273.15 |       |


| Entrada | Saida |
| ------- | ----- |
| C       | 32.0  |
| F       |       |
| 0       |       |

> Dizer que sua solução deve possuir precisão de, no mínimo, duas casas decimais significa dizer que a diferença entre sua solução e a solução esperada deve ser, no máximo, 0.01.

</details>