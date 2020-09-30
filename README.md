# Flutter - Trabalhe com listas longas

O construtor ListView padrão funciona bem para listas pequenas. Para trabalhar com listas que contêm um grande número de itens, é melhor usar o construtor ListView.builder.  
Em contraste com o construtor ListView padrão, que requer a criação de todos os itens de uma vez, o construtor ListView.builder () cria itens conforme eles são rolados na tela.

# Crie uma fonte de dados
Primeiro, você precisa de uma fonte de dados. Por exemplo, sua fonte de dados pode ser uma lista de mensagens, resultados de pesquisa ou produtos em uma loja. Na maioria das vezes, esses dados vêm da Internet ou de um banco de dados.

Para este exemplo, gere uma lista de 10.000 Strings usando o construtor List.generate.

`final items = List<String>.generate(10000, (i) => "Item $i");`

