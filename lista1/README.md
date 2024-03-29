# Assembly-mips: lista 1
Resoluções de problemas de lógica com assembly mips

## A: Ola mundo
<details>
<summary>olamundo.spim</summary>
Olá!

Você está iniciando no mundo da correção automática de exercícios de computação. Este é um momento bastante delicado e por isso você deve prestar atenção em todos os detalhes de um problema.

A primeira coisa que devemos perceber é que sempre que se fala em linha devemos entender que a linha termina com o caractere de quebra de linha o \n, também é interessante saber que os sistemas de correção automática executam um sistema UNIX, em geral Linux e por isso a quebra de linha é composta unicamente pelo caractere \n, os sistemas (r)Windows utilizam o conceito \r\n.

Para este problema você deve imprimir uma única linha contendo a frase:

Ola Mundo
</details>

## B: Soma 2
<details>
<summary>soma2.spim</summary>
Bem vindo ao segundo exercício!

No exercício anterior trabalhamos apenas com a impressão de uma única linha, agora vamos interagir com a máquina!!!

Todos os exercícios com correção automática possuem um processamento de uma entrada e o seu resultado é impresso em uma ou mais linhas.

Para este exercício você deve ler 2 números da entrada padrão (geralmente o teclado) e imprimir uma única linha contendo a soma destes 2 números.

Entrada:

A entrada é composta por dois números inteiros N_i ( 0 \leq N_i \leq 600000 ).

Saída:

A saída é composta por uma única linha contendo a somas dos dois números inteiros lidos, veja abaixo alguns exemplos de entradas e saídas.
</details>

## C: Pneu
<details>
<summary>subtrai2.spim</summary>
Calibrar os pneus do carro deve ser uma tarefa cotidiana de todos os motoristas. Para isto, os postos de gasolina possuem uma bomba de ar. A maioria das bombas atuais são eletrônicas, permitindo que o motorista indique a pressão desejada num teclado. Ao ser ligada ao pneu, a bomba primeiro lê a pressão atual e calcula a diferença de pressão entre a desejada e a lida. Com esta diferença ela esvazia ou enche o pneu para chegar na pressão correta.

Sua ajuda foi requisitada para desenvolver o programa da próxima bomba da SBC - Sistemas de Bombas Computadorizadas.

Escreva um programa que, dada a pressão desejada digitada pelo motorista e a pressão do pneu lida pela bomba, indica a diferença entre a pressão desejada e a pressão lida.

Entrada:

A primeira linha da entrada contém um inteiro N que indica a pressão desejada pelo motorista ( 1 \leq N \leq 40 ). A segunda linha contém um inteiro M que indica a pressão lida pela bomba ( 1 \leq M \leq 40 ).

Saída:

Seu programa deve imprimir uma única linha, contendo a diferença entre a pressão desejada e a pressão lida.
</details>

## D: Notas da prova
<details>
<summary>notas.spim</summary>
Rosy é uma talentosa professora do Ensino Médio que já ganhou muitos prêmios pela qualidade de sua aula. Seu reconhecimento foi tamanho que foi convidada a dar aulas em uma escola da Inglaterra. Mesmo falando bem inglês, Rosy ficou um pouco apreensiva com a responsabilidade, mas resolveu aceitar a proposta e encará-la como um bom desafio.

Tudo ocorreu bem para Rosy até o dia da prova. Acostumada a dar notas de 0 (zero) a 100 (cem), ela fez o mesmo na primeira prova dos alunos da Inglaterra. No entanto, os alunos acharam estranho, pois na Inglaterra o sistema de notas é diferente: as notas devem ser dadas como conceitos de A a E. O conceito A é o mais alto, enquanto o conceito E é o mais baixo.

Conversando com outros professores, ela recebeu a sugestão de utilizar a seguinte tabela, relacionando as notas numéricas com as notas de conceitos:

|Nota	   | Conceito |
|----------|----------|
|0	       |    E     |
|1 a 35	   |    D     |
|36 a 60   |    C     |
|61 a 85   |    B     |
|86 a 100  |    A     |

O problema é que Rosy já deu as notas no sistema numérico, e terá que converter as notas para o sistema de letras. Porém, Rosy precisa preparar as próximas aulas (para manter a qualidade que a tornou reconhecida), e não tem tempo suficiente para fazer a conversão das notas manualmente.

Entao, você deve escrever um programa que receba uma nota no sistema numérico e determine o conceito correspondente.

Entrada:

A entrada é composta por uma única linha contendo um inteiro N ( 0 \leq N \leq 100 ) que indica uma nota de prova no sistema numérico.

Saída:

A saída é composta de uma única linha, contendo a letra A, B, C, D ou E (em maiúsculas) representando o conceito correspondente a nota dada na entrada.
</details>

## E: Piramides
<details>
<summary>piramide.spim</summary>
Faça um programa que leia um número natural n e desenhe uma pirâmide de asteriscos (veja o exemplo de saída).

Entrada:

A entrada é composta por uma única linha, contendo o número n ( 1 \leq n \leq 1000000 ).

Saída:

A saída é composta pela pirâmide de asteriscos.

</details>

## F: Maior numero
<details>
<summary>maiornumero.spim</summary>
O objetivo neste exercício é simples: você deve ler n números e determinar o maior entre eles.

Entrada:

A entrada é composta por diversas linhas. A primeira linha contém um inteiro n (1 \leq n \leq 10^5). As n linhas seguintes contém cada uma um inteiro.

Saída:

A saída é composta por uma única linha contendo o maior dos n números lidos.
</details>

## G: Bit de paridade
<details>
<summary>paridade.spim</summary>
Um bit de paridade, ou um bit de conferência, é um bit adicionado a uma string de um código binário de forma que a string composta possua um número total de bits 1 par (paridade par) ou ímpar (paridade ímpar). Bits de paridade são uma das formas mais simples de códigos de detecção de erro e foram utilizados nos primórdios da Internet na proteção dos dados transmitidos pelos modems, dados que trafegavam em links de comunicação seriais, geralmente providos pelo par trançado das linhas telefônicas.

Há duas variantes para o cálculo de bits de paridade: a paridade par e a paridade ímpar. No caso da paridade par, para um conjunto de bits, as ocorrências dos bits cujo valor é 1 são contadas. Se a contagem total resultar em um número ímpar, o bit de paridade é ajustado para 1, fazendo com que a quantidade de ocorrências de 1 no conjunto (incluindo o bit de paridade) seja um número par. Se a contagem de 1s em determinado conjunto de bits já for par, o bit de paridade é ajustado para 0.

O bit de paridade pode ser colocado na posição mais significativa da palavra resultante.

Sua tarefa é implementar um procedimento que receba em $a0 um número menor que 128 e processe o número lido calculando o valor de bit necessário à ser adicionado para que a quantidade de bits 1 seja um número par. O seu procedimento deve retornar o bit de paridade em $v0 e o número resultante em $v1. Veja exemplos abaixo.

ATENÇÃO: você deve enviar apenas o código referente ao procedimento bitparidade, sem enviar as declarações de .text e .data.

- no arquivo paridade-completo.spim há o codigo com .data e .text para ser executado, e no aquivo paridade.spim há somente o procedimento
</details>