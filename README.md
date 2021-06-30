# Calculadora de alcance de anúncio

Parte 1 do desafio da seleção para Academia Capgemini.


 * [Descrição](##Descrição)
 * [Status do Arquivo ](##Status)
 * [Features](##Features)
 * [Como rodar a aplicação](##ComoRodar)
 * [Tecnologia](##Tecnologia)
 * [Autora](##Autora)


## Descrição

Projeto criado como requisito da seleção da Academia Capigemini.

O projeto é de uma calculadora que recebe um valor de investimento diário e retorna uma projeção aproximada da quantidade máxima de pessoas que visualizarão o anúncio.

O arquivo executa o cálculo da quantidade máxima de visualizações, que o anúncio terá após ser compartilhado pela empresa Divulga Tudo, seguindo a lógica:

1 real -> 30 views
100 views ->12 clicks
20 clicks -> 3 compartilhamentos
1 compartilhamento -> mais 40 views

Mas o anúncio só pode ser compartilhado 4 vezes, sendo uma vez pela anunciante, de forma que o anuncio alcança no máximo a 4ª pessoa em sequencia (anunciante -> 1ª -> 2ª -> 3ª -> 4ª)

Na lógica do arquivo, foi criada uma função 'calculaloop' que altera os valores das visualizações. cliques e compartilhaments a cada novo compartilhamento. (no máximo 3, considerando que o anúncio chega até a 4ª pessoa no máximo)

E a função gera relatório que é quem recebe de fato o valor investido e retorna o máximo de visualizações alcançadas pelo anúncio.

Não são exibidos números decimais porque "no máximo 30,6 visualizações" são 30 visualizações.

## Status do Arquivo 

Desafio concluído e entregue.

## Features

- [x] Captura do valor informado pelo usuário
- [x] Calcula o alcance do anúncio
- [x] Exibe no console o resultado do cálculo


## Como rodar a aplicação


Para executar o programa, é necessario ter o node instalado em sua máquina, e a interação ocorrerá pelo console.

> node calculadora.js


## Tecnologia

- JavaScript

## Autora

Alice de Fátima Moraes Souza

github: https://github.com/alicefms

linkedIn: https://www.linkedin.com/in/alice-moraes-189810101/
