# Projeto Estacionamento - Trilha .NET 🚗
By: dio.me

## Desafio de projeto ESTACIONAMENTO COM C#
Onde seram implementadoa os conhecimentos adquiridos no módulo de fundamentos, da trilha .NET da DIO.

## Contexto
Sistema para um estacionamento no qual tem a função de gerenciar os veículos estacionados e realizar operações, tais com adicionar um veículo, remover um veículo (e exibir o valor cobrado durante o período) e listar os veículos.

## Proposta
A CLASSE principal chamada "Estacionamento", será baseada no diagrama:

![Diagrama de classe estacionamento](diagrama_classe_estacionamento.png)

##
A CLASSE principal contém três variáveis, sendo:

**precoInicial**: Tipo decimal. É o preço cobrado para deixar seu veículo estacionado.

**precoPorHora**: Tipo decimal. É o preço por hora que o veículo permanecer estacionado.

**veiculos**: É uma lista de string, representando uma coleção de veículos estacionados. Contém apenas a placa do veículo.

A classe contém três métodos, sendo:

**AdicionarVeiculo**: Método responsável por receber uma placa digitada pelo usuário e guardar na variável **veiculos**.

**RemoverVeiculo**: Método responsável por verificar se um determinado veículo está estacionado, e caso positivo, irá pedir a quantidade de horas que ele permaneceu no estacionamento. Após isso, realiza o seguinte cálculo: **precoInicial** * **precoPorHora**, exibindo para o usuário.

**ListarVeiculos**: Lista todos os veículos presentes atualmente no estacionamento. Caso não haja nenhum, exibir a mensagem "Não há veículos estacionados".

## Usabilidade
Será disposto um Menu interativo com as seguintes ações implementadas:
1. Cadastrar veículo
2. Remover veículo
3. Listar veículos
4. Encerrar
