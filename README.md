# Projeto: LOTOFÁCIL em Java

## Descrição
Este projeto implementa um sistema de loteria chamado LOTOFÁCIL em Java. O sistema é capaz de gerar jogos aleatórios, permitir que os jogadores façam suas apostas, verificar os resultados e calcular prêmios de acordo com as regras da loteria. O sistema funciona por meio do terminal, lendo e escrevendo dados.

## Regras de negócio/requisitos:

### Regras para a aposta de 0 a 100:
- Utilizando a biblioteca Scanner, leia um número inteiro via teclado, de 0 a 100. Caso o número seja maior que 100 ou menor que 0, imprima a mensagem: “Aposta inválida.”.
- Utilize a biblioteca Random para sortear aleatoriamente um número de 0 a 100.
- Compare o número escolhido pelo usuário apostador com o número sorteado pelo sistema.
- Caso o usuário acerte a aposta, imprima a mensagem “Você ganhou R$ 1.000,00 reais.”. Caso o usuário erre, imprima a mensagem: “Que pena! O número sorteado foi: X.”.

### Regras para a aposta de A à Z:
- Utilizando o método System.in.read(), leia um char via teclado, de A à Z, podendo ser lido como maiúsculo ou minúsculo. Caso não seja uma letra, imprima a mensagem: “Aposta inválida.”.
- Converta a entrada do usuário apostador para maiúsculo, utilizando o método Character.toUpperCase().
- Escolha a letra com a inicial do seu nome para ser a letra premiada. Exemplo: char letraPremiada = 'J'.
- Compare a letra lida via teclado, e convertida para maiúsculo, com a letra premiada.
- Caso o usuário acerte a aposta, imprima a mensagem “Você ganhou R$ 500,00 reais.”. Caso o usuário erre, imprima a mensagem: “Que pena! A letra sorteada foi: X.”.

### Regras para a aposta de número par ou ímpar:
- Utilizando a biblioteca Scanner, leia um número inteiro via teclado.
- Utilize o operador de módulo (%) para verificar se o número é par ou ímpar.
- O prêmio será dado caso o usuário digite um número par. O sistema não irá premiar jogadores que digitarem um número ímpar.
- Se o número digitado for par, imprima a mensagem: “Você ganhou R$ 100,00 reais.”. Caso o usuário digite um número ímpar, imprima a mensagem: “Que pena! O número digitado é ímpar e a premiação foi para números pares.”.

## Documentação adicional:
- [Documentação da classe Scanner](https://docs.oracle.com/javase/8/docs/api/java/util/Scanner.html)
- [Documentação da classe Random](https://docs.oracle.com/javase/8/docs/api/java/util/Random.html)
- [Documentação da classe Character](https://docs.oracle.com/javase/8/docs/api/java/lang/Character.html)

## Versão do JDK
O projeto foi desenvolvido e testado utilizando o JDK versão 8.

## Bibliotecas Utilizadas
Este projeto utiliza as bibliotecas padrão do Java: Scanner, Random e Character.

Este README.md fornece uma visão geral do projeto LOTOFÁCIL em Java, incluindo uma descrição do projeto, requisitos e instruções sobre como executá-lo, bem como informações sobre a versão do JDK e as bibliotecas utilizadas. Certifique-se de ajustar as informações conforme necessário para o seu projeto específico.

Se precisar de mais alguma coisa, estou à disposição para ajudar!
