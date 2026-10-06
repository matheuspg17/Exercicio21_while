# Resolução Exercicio21_while

## Descrição do problema 
Escreva um programa em Java que mostre todos os números pares entre 33 e 57
usando while.

## Como Funciona
1. O algoritmo define o ponto de partida na variável `i = 34`, que corresponde ao primeiro número par válido dentro do intervalo solicitado (já que 33 é ímpar).
2. A estrutura de repetição `while (i < 57)` avalia e executa o bloco de código enquanto o valor atual não atingir o limite superior do intervalo.
3. Dentro do laço, a instrução `System.out.println(i)` imprime o número par corrente.
4. Para otimizar o processamento e evitar testes condicionais desnecessários, a variável de controle é incrementada diretamente de duas em duas unidades (`i += 2`), saltando direto para o próximo número par da sequência.