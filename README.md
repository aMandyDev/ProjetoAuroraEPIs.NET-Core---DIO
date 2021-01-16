![Aurora Project](https://repository-images.githubusercontent.com/128673011/f6ebdd80-b6da-11ea-94bb-9d141944b257)

# What is Aurora project?
It's an open source project, written in .NET Core, currently in version 3.1.

The project's goals is to show that is possible to create an architecture more simple than others and using some concepts like DDD (Design Driven Design).

## Business proposal:
This project is a simple PPE (Personal Protective Equipament) Management. The principle idea is to register workers and PPE and, with this data, allow to transfer PPE to a worker.
Besides that, this system allow that you see all PPE and who has a PPE and notify if the PPE is near to expire.

### Abbreviations:
* NIN: National Insurance Number (as CPF in Brazil)

## How to use:
1. Clone this project to into your machine
2. Use the default connection string or:
    2.1. Install and configure [MySql](https://dev.mysql.com/downloads/mysql/), if you want.
    2.2. Inform the connection string on Aroura.Infra.Data/Context/MySqlContext.cs, if necessary
    * Put the server name on [SERVER] tag
    * Put the port number on [PORT] tag
    * Put the user name database on [USER] tag
    * Put the password database on [PASSWORD] tag
4. Finally, build and run the application

## MySql Migrations:
1. Open your Package Manager Console
2. Change the default project to Aurora.Infra.Data
3. Run command "Add-Migration [NAME OF YOUR MIGRATION]"
4. Run command "Update-Database"

For more information about this project, sse this [article](https://medium.com/@alexalves_85598/criando-uma-api-em-net-core-baseado-na-arquitetura-ddd-2c6a409c686).

## Technologies implemented:
* ASP.NET Core 3.1 (com .NET Core 3.1)
* Entity Framework Core 3.1.5
* Flunt Validation 1.0.5
* Swagger UI 5.5.0
* MySql Database Connection
* .NET Core Native DI
* SpecFlow for BDD
* GitHub Actions

## Architecture:
* Layer architecture
* S.O.L.I.D. principles
* Clean Code
* Domain Validations
* Domain Notifications
* Domain Driven Design
* Repository Pattern
* Notification Pattern
* Mapper by Extension Methods
* Value Types
* BDD (Behavior Driven Development)

![Architecture](https://miro.medium.com/max/962/1*qpHCIA7RDfW89KtSUXGJog.png)

## News:
**v1.4 --- 2020-09-28**
* CI/CD by GitHub Actions
* Include integration tests using BDD with SpecFlow
    * scenario of register a worker
    * scenario of update a worker
* Bug corrections

**v1.3 --- 2020-07-30**
* Changed some Primitive Types to Value Types
* Changed the business idea principle

**v1.2 --- 2020-06-30**
* Implemented Notification Pattern
* Implemented Domain Validations and Notifications
* Using some concepts of Clean Architecture
    * Entities
    * Interface Adapters
* Changed the framework validations to Flunt
* Using mapper by extension methods

**v1.1 --- 2020-06-24**
* Updated the project name
* Updated the project's SDK to .NET Core 3.1 version
* Added the Swagger framework to document the API
* Corrections to end-points
* Published in [Azure](http://aurora-project.azurewebsites.net/swagger/index.html)

**v1.0 --- 2018-06-09**
* Create the project in .NET Core 2.0 version
* Structured the project on layer architecture 
* Used the Service layer to business rules
* Used the FluentValidation library
* Configured the connection to MySql database
* Used EntityFramework

## Why Aurora?
The name Aurora came from the natural event called Aurora Borealis. It is a scientific event described by the interaction between the earth's magnetic layer and energized particles from the solar wind.

A curiosity about such an event is that what we see in photographs is not always the same image that is seen live.

For more information, look this [link](https://www.hipercultura.com/fenomenos-naturais/).

## We're online!
See the project in [Azure](http://aurora-project.azurewebsites.net/swagger/index.html).

## About:
The Aurora project was developed by [Alex Alves](https://www.linkedin.com/in/alexalvess/).! [Aurora Project] (https://repository-images.githubusercontent.com/128673011/f6ebdd80-b6da-11ea-94bb-9d141944b257)

## Tradução

# O que é o projeto Aurora?

É um projeto de código aberto, escrito em .NET Core, atualmente na versão 3.1.

O objetivo do projeto é mostrar que é possível criar uma arquitetura mais simples do que outras e utilizando alguns conceitos como DDD (Design Driven Design).

## Proposta de negócio:

Este projeto é uma gestão simples de EPI (Equipamentos de Proteção Individual). A ideia principal é cadastrar trabalhadores e EPIs e, com esses dados, permitir a transferência de EPIs para um trabalhador.

Além disso, este sistema permite que você veja todos os EPIs e quem possui um EPI e avise se o EPI está prestes a expirar.

### Abreviações:

* NIN: Número do Seguro Nacional (como CPF no Brasil)

## Como usar:

1. Clone este projeto em sua máquina

2. Use a string de conexão padrão ou:

  2.1. Instale e configure [MySql] (https://dev.mysql.com/downloads/mysql/), se desejar.

  2.2. Informe a string de conexão em Aroura.Infra.Data/Context/MySqlContext.cs, se necessário

  \* Coloque o nome do servidor na tag [SERVER]

  \* Coloque o número da porta na tag [PORT]

  \* Coloque o banco de dados de nome de usuário na tag [USER]

  \* Coloque o banco de dados de senha na tag [PASSWORD]

4. Por fim, crie e execute o aplicativo

## Migrações do MySql:

1. Abra o console do gerenciador de pacotes

2. Altere o projeto padrão para Aurora.Infra.Data

3. Execute o comando "Add-Migration [NAME OF YOUR MIGRATION]"

4. Execute o comando "Update-Database"

 

Para mais informações sobre este projeto, consulte este [artigo] (https://medium.com/@alexalves_85598/criando-uma-api-em-net-core-baseado-na-arquitetura-ddd-2c6a409c686).

## Tecnologias implementadas:

* ASP.NET Core 3.1 (com .NET Core 3.1)

* Entity Framework Core 3.1.5

* Validação Flunt 1.0.5

* Swagger UI 5.5.0

* Conexão de banco de dados MySql

* .NET Core Native DI

* SpecFlow para BDD

* Ações GitHub

## Arquitetura:\* Arquitetura de camadas\* S.O.L.I.D. princípios\* Código limpo\* Validações de domínio

* Notificações de domínio

* Design Orientado por Domínio

* Padrão de Repositório

* Padrão de Notificação

* Mapeador por Métodos de Extensão

* Tipos de valor

* BDD (Behavior Driven Development)

! [Arquitetura] (https://miro.medium.com/max/962/1*qpHCIA7RDfW89KtSUXGJog.png)

## Notícia:

** v1.4 --- 2020-09-28 **

* CI / CD por GitHub Actions

* Inclui testes de integração usando BDD com SpecFlow  \* cenário de registrar um trabalhador

 \* cenário de atualização de um trabalhador

* Correções de bugs

 

** v1.3 --- 2020-07-30 **

* Alterado alguns tipos primitivos para tipos de valor

* Mudou o princípio da ideia de negócio

 

** v1.2 --- 2020-06-30 **

* Padrão de Notificação Implementado

* Validações e notificações de domínio implementadas

* Usando alguns conceitos de Arquitetura Limpa

  \* Entidades

  \* Adaptadores de interface

* Mudou as validações de framework para Flunt

* Usando mapeador por métodos de extensão

 

** v1.1 --- 2020-06-24 **

* Atualizado o nome do projeto

* Atualizado o SDK do projeto para a versão .NET Core 3.1

* Adicionada a estrutura Swagger para documentar a API

* Correções para pontos finais

* Publicado em [Azure] (http://aurora-project.azurewebsites.net/swagger/index.html)

 

** v1.0 --- 09/06/2018 **

* Crie o projeto na versão .NET Core 2.0

* Estruturei o projeto em arquitetura de camadas

* Usou a camada de serviço para regras de negócios

* Usou a biblioteca FluentValidation

* Configurou a conexão com o banco de dados MySql

* EntityFramework usado

 

## Por que Aurora?

O nome Aurora veio do evento natural denominado Aurora Borealis. É um evento científico descrito pela interação entre a camada magnética da Terra e as partículas energizadas do vento solar.

Uma curiosidade sobre tal evento é que o que vemos nas fotos nem sempre é a mesma imagem que vemos ao vivo.

Para obter mais informações, consulte este [link] (https://www.hipercultura.com/fenomenos-naturais/).

## Estamos online!

Veja o projeto em [Azure] (http://aurora-project.azurewebsites.net/swagger/index.html).

## Sobre:

O projeto Aurora foi desenvolvido por [Alex Alves] (https://www.linkedin.com/in/alexalvess/).