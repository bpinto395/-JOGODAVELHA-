# JOGO DA VELHA # 

## Objetivo: 

### 1- desenvolver um jogo da velha que possa rodar com dois usuarios 
o Aplicativo deve diferenciar antes de iniciar a partida dois usuarios com dois simbolos X e O 
> ao iniciar o jogo deve dar as duas opções para escolha de cada usuario a partir desse momento cada usuario é definido por seu simbolo 

### 2- A criação de um tabuleiro bem definido de 9 espaços
que se dividem em 3 linha e 3 colunas 
> Uma grade de 3x3

### 3- O jogo deve definir um resultado 
quando os 9 espaços forem ocupados o jogo deve apontar um vencedor ou o empate 
> De acordo com a RJ004 e a RJ005

## Regras do Jogo: 

### RJ001: 
É nescessário que os usuarios preencha um dos 9 espaços com um simbolo ( X e O )
### RJ002: 
Os usuarios devem alternar entre uma jogada e outra
### RJ003: 
Não se pode por um simbolo sobre o outro
### RJ004:
O vencedor é quem enfilerar 3 vezes seu simbolo, na horizontal, vertical ou diagonal
### RJ005: 
Caso nenhum usuario consiga a RJ004 o jogo é definido como empate

## Interação Usuario e Grade:

### IUG001: 
O tabuleiro é formado por uma grade de 3x3 para facilitar será chamado de grade durante a programação
### IUG002: 
O usuario após escolher seu simbolo será apresentado a grade tendo de selecionar o campo e colocar o X ou o O
### IUG003: 
Caso o usuario desrespeite as regras a grade deve retornar informando erro
### IUG004: 
assim que se informar o vencedor deve-se disponibilizar a possibilidade de reiniciar o jogo



