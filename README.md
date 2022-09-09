# TFC

O TFC é um site informativo sobre partidas e classificações de futebol! :soccer:

O objetivo é desenvolver uma API (utilizando o método TDD) e também integrar - através do docker-compose - as aplicações para que elas funcionem consumindo um banco de dados.

Construir um back-end dockerizado utilizando modelagem de dados através do Sequelize. O desenvolvimento deve respeitar regras de negócio providas no projeto e a API deve ser capaz de ser consumida por um front-end já provido nesse projeto.

Para adicionar uma partida é necessário ter um token, portanto a pessoa deverá estar logada para fazer as alterações. Teremos um relacionamento entre as tabelas teams e matches para fazer as atualizações das partidas.

O seu back-end deverá implementar regras de negócio para popular adequadamente a tabela disponível no front-end que será exibida para a pessoa usuária do sistema.

## 🚀 Começando

* 1° - Clone este repositório na sua máquina.
* 2° - Instale as dependências com o ```npm install```.
* 3° - Configure suas variáveis de ambiente.
* 4° - Rode, na raiz do projeto, o comando ```npm run compose:up```
* 5° - Acesse no seu navegador, a página localhost:3000.

### 📋 Pré-requisitos

* Sistema Operacional Distribuição Unix

* Node versão 16

* Docker

* Docker-compose versão >=1.29.2

:arrow_right: O node deve ter versão igual ou superior à 16.15.0 LTS.

:arrow_right: O docker-compose deve ter versão igual ou superior àˆ1.29.2.

### 🔧 Demonstração

![Demonstração](https://github.com/lucaadev/TFC/blob/main/Demonstra%C3%A7%C3%A3o.gif)

## ⚙️ Executando os testes

Rode o comando ```npm run test``` para rodar os testes de integração.


## 🛠️ Construído com

Mencione as ferramentas que você usou para criar seu projeto

* [Express](https://expressjs.com/pt-br/)
* [NodeJs](https://nodejs.org/en/)
* [Docker](https://www.docker.com/)
* [Sequelize](https://sequelize.org/)
* [MySQL](https://www.mysql.com/)
* [Jest](https://jestjs.io/pt-BR/)
* [Mocha](https://mochajs.org/)
* [JWT](https://www.npmjs.com/package/jsonwebtoken)

## 📌 Versão

Usamos [Git](https://git-scm.com/) para controle de versão.
## ✒️ Autores

* **Lucas Junqueira** - *Back-End* - [GitHub](https://github.com/lucaadev)
* **Trybe** - *Front-End* - [GitHub](https://github.com/tryber)
