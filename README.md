# :construction: Projeto Unit Tests :construction:
Este projeto consiste em implementar testes automatizados para diversas funções JavaScript usando a biblioteca Jest. Abaixo está uma visão geral das funções testadas e seus respectivos testes:

## Função circle:

A função circle recebe o raio de um círculo e retorna um objeto contendo suas informações: Raio, Área e Circunferência.
Se o raio não for especificado, a função retorna undefined.
Os testes garantem que a função retorna corretamente os valores esperados para diferentes raios e verifica se a função retorna undefined quando o parâmetro não é um número.
## Função getCharacter:

A função getCharacter recebe o nome de um personagem e retorna um objeto contendo seu nome, classe e frases.
Os testes garantem que a função retorne corretamente os detalhes dos personagens para os nomes especificados e se a função retorna undefined para um nome não encontrado na tabela.
Além disso, testa se a função é insensível a maiúsculas e minúsculas nos nomes dos personagens.
## Função numbers:

A função numbers recebe um array e retorna true se todos os elementos do array forem do tipo 'number' e false caso contrário.
Os testes garantem que a função retorne corretamente true apenas se todos os elementos do array forem números e false caso contrário.
## Função productDetails:

A função productDetails recebe dois nomes de produtos e retorna um array contendo objetos com os detalhes dos produtos.
Os testes garantem que a função retorne corretamente os objetos com os detalhes dos produtos para os nomes especificados, além de verificar se os dois objetos retornados são diferentes entre si.
## Função createMenu:

A função createMenu retorna um objeto com um método fetchMenu, que retorna um objeto contendo as chaves "food" e "drinks".
Os testes garantem que a função createMenu retorne corretamente um objeto com a chave fetchMenu e que o método fetchMenu retorne um objeto com as chaves "food" e "drinks".

## Conclusão
Esses testes garantem que as funções implementadas estão comportando-se conforme o esperado e ajudam a garantir a qualidade do código JavaScript desenvolvido.

## Pastas e Arquivos
A pasta /src com todos os arquivos e códigos criados são de autoria da Trybe.

A pasta /tests com todos os aquivos e códigos implementados são de autoria minha [Fernando Álisson].