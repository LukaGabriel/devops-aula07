# Arquitetura

## Inicialização do tabuleiro

* As funções relacionadas ao gerenciamento das casas do jogo da velha ficarão
no módulo **jogovelha.py**.

* O estado de cada casa do jogo será representada por uma string: "." para casa
vazia; "X" para casa ocupada pelo 1o jogador; "O" para casa ocupada pelo 2o
jogador.

* A função inicializar() retornará uma lista 3x3, onde cada posição conterá uma
string para indicar o estado de uma casa do jogo. A função retornará todas as
casas inicialmente vazias.

* A função jogar(jogador, linha, coluna) irá posicionar o **jogador** ('X' ou
'O') na posição definida por **linha** e **coluna**.

## Verificação da validade das jogadas

* A implementação deverá ser realizada no arquivo **jogovelhe.py**.

* Ela deverá ter uma nova função verificando se a casa escolida pelo jogador está vazia e retornar um valor de verdadeiro e falso.
