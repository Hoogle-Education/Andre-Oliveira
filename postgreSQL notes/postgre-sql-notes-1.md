# Introdução a banco de dados

## Tabela 

A tabela é uma organização de dados em listas, baseadas em colunas de dados.

> A princípio toda tabela será vista como uma lista.

## Chave primária

Análoga CPF, indentificador único para os objetos cadastrados em uma tabela.

## Chave estrangeira

é uma chave que permite a conexão com a chave primária de outra tabela.

***Seller table***
|id|Name|Email|BirthDate|DepartmentID|
|:-:|:-:|:-:|:-:|:-:|
|1|Maria|maria@gmail.com|2200.0|2|
|2|Alex|alex@gmail.com|2000.0|3|

***department table***
|id|Name|
|:-:|:-:|
|1|Food|
|2|Technology|
|3|Clothes|

## Principais operações (`CRUD`)

```
CREATE
RETRIEVE 
UPDATE
DELETE
```

## Indice

Utiliza uma estrutura de dados para organizar os dados de forma mais inteligente baseado em algum dado dito como relevante.

> Utiliza árvores para fazer estas operações

Escolha critérios relevantes ou pares de crtérios relevantes para sua busca.
