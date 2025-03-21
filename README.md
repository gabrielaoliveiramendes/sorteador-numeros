# Gerador de Números Aleatórios Personalizado

## Introdução

Este repositório apresenta o código JavaScript desenvolvido para um gerador de números aleatórios personalizado. O projeto foi implementado sobre uma base já existente, que incluía a estrutura HTML e o design CSS da aplicação. O foco principal deste trabalho foi criar a lógica JavaScript necessária  permitindo ao usuário definir a quantidade de números a serem sorteados, o intervalo mínimo e máximo, e garantindo que os números sorteados sejam únicos.

## Funcionalidades Principais
- Entrada do Usuário: O código captura os valores inseridos pelo usuário nos campos "Quantidade", "Do número" e "Até o número" para personalizar a geração dos números aleatórios.
- Validação de Dados: Antes de gerar os números, o código verifica se os valores inseridos pelo usuário são válidos, garantindo que o intervalo mínimo seja menor que o máximo e que a quantidade de números solicitada seja menor ou igual ao tamanho do intervalo.
- Geração de Números Aleatórios: A função obterNumeroAleatorio() utiliza Math.random() para gerar um número aleatório dentro do intervalo especificado.
- Eliminação de Duplicatas: A função sortear() utiliza um array (sorteados) para armazenar os números já sorteados e um loop while para garantir que cada número sorteado seja único.
- Interface do Usuário: O código interage com o HTML para exibir os resultados e habilitar/desabilitar o botão de reiniciar conforme necessário.
- Estilo Visual: O código utiliza a propriedade classList para alterar o estilo do botão de reiniciar, indicando se está habilitado ou desabilitado.

## Conceitos de JavaScript Utilizados
- Estrutura de Repetição for: Utilizada para gerar a quantidade especificada de números aleatórios.
- Arrays: O array sorteados armazena os números já sorteados, permitindo verificar se um número já foi sorteado anteriormente.
- if/else: Utilizado para verificar condições e tomar decisões, como validar os dados de entrada e alterar o estado do botão.
- classList: Propriedade que permite adicionar, remover ou verificar classes em um elemento HTML, controlando o estilo visual do botão.
- parseInt: Converte uma string em um número inteiro, permitindo trabalhar com os valores numéricos inseridos pelo usuário.
- Math.random() e Math.floor: Utilizados para gerar números aleatórios dentro de um intervalo específico.
- includes(): Verifica se um array contém um determinado elemento.

## Como Funciona
- Entrada do Usuário: O usuário insere a quantidade de números desejados, o valor mínimo e o valor máximo.
- Validação: O código verifica se os valores inseridos são válidos.
- Geração de Números: Um loop for gera a quantidade de números solicitada.
- Verificação de Duplicatas: A cada número gerado, o código verifica se ele já existe no array sorteados. Se sim, um novo número é gerado.
- Exibição dos Resultados: Os números sorteados são exibidos na página HTML.
- Botão de Reiniciar: O botão é habilitado após a geração dos números e desabilitado enquanto o usuário não inserir novos valores.
