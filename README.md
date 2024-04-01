# Projeto Lotofácil

Este projeto consiste na implementação de um sistema de loteria chamado **Lotofácil** em Java. O sistema permite que os jogadores façam suas apostas em diferentes modalidades, verifiquem os resultados e calculem os prêmios de acordo com as regras da loteria. O sistema funciona através do terminal, lendo e escrevendo dados.

## Funcionalidades

O sistema oferece as seguintes funcionalidades:

1. **Apostar de 0 a 100**: Permite que o jogador faça uma aposta em um número inteiro de 0 a 100.
2. **Apostar de A à Z**: Permite que o jogador faça uma aposta em uma letra de A a Z.
3. **Apostar em número par ou ímpar**: Permite que o jogador faça uma aposta em um número inteiro e verifica se é par ou ímpar.

## Menu Lotofácil

```
**************************
Menu LOTOFÁCIL:
1) Apostar de 0 a 100
2) Apostar de A à Z
3) Apostar em par ou ímpar
0) Sair
**************************
```

## Regras de Negócio

### Apostar de 0 a 100
- O jogador deve escolher um número inteiro de 0 a 100.
- Se o número estiver fora deste intervalo, uma mensagem de "Aposta inválida." será exibida.
- O sistema sorteará aleatoriamente um número de 0 a 100.
- Se o jogador acertar a aposta, receberá um prêmio de R$ 1.000,00. Caso contrário, será informado o número sorteado.

### Apostar de A à Z
- O jogador deve escolher uma letra de A a Z.
- Se a entrada não for uma letra, será exibida a mensagem "Aposta inválida.".
- A letra premiada é determinada pela inicial do nome do desenvolvedor.
- Se o jogador acertar a letra premiada, receberá um prêmio de R$ 500,00. Caso contrário, será informada a letra premiada.

### Apostar em número par ou ímpar
- O jogador deve escolher um número inteiro.
- O sistema verifica se o número é par ou ímpar.
- Se o número for par, o jogador ganhará um prêmio de R$ 100,00. Caso contrário, será informado que a premiação é para números pares.

## Execução

Para executar o sistema, basta compilar os arquivos Java e executar o arquivo principal. O sistema mostrará o menu Lotofácil, onde o jogador poderá fazer suas apostas.
