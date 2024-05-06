# m6-s3

Este README contém o modelo lógico de um banco de dados destinado a explicar o armazenamento de dados sobre o transporte de pacientes e produtos médicos. O banco de dados está hospedado na Amazon RDS, utilizando o MySQL.

## Diagrama do Modelo Lógico

Abaixo está o diagrama do modelo lógico do banco de dados:

<h6 align="center"> Figura 1: Modelo Lógico</h6>

<div style="text-align: center;">
  <img src="./imagens/modelo_logico.png">
</div>

Este diagrama foi criado utilizando a ferramenta web BRModelo, e ilustra as tabelas, suas relações, chaves primárias, chaves estrangeiras e outros atributos relevantes.

## Configuração do Ambiente

### Conexão com o Banco de Dados

Não consegui conectar com o banco de dados. Tentei conectar no phpMyAdmin utilizando o docker-compose do professor Romualdo:

<h6 align="center"> Figura 2: Docker compose rodando</h6>

<div style="text-align: center;">
  <img src="./imagens/containers_rodando.png">
</div>

<h6 align="center"> Figura 3: Erro com phpMyAdmin</h6>

<div style="text-align: center;">
  <img src="./imagens/pma.png">
</div>

tentei também no dbeaver:

<h6 align="center"> Figura 4: Erro com DBeaver</h6>

<div style="text-align: center;">
  <img src="./imagens/dbeaver.png">
</div>

por fim, testei uma conexão dierta usando o comando telnet:

<h6 align="center"> Figura 5: Erro com telnet</h6>

<div style="text-align: center;">
  <img src="./imagens/telnet.png">
</div>

Habilitei todas as portas e IP's a acesrem o RDS mas ainda não consegui.

## Realizando Queries no Banco de Dados

&emsp;&emsp;Ainda que não consegui conectar, a query para calcular o número médio de pacientes transportados por veículo por mês seria:

```

```
