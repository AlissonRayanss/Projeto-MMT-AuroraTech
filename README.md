# Projeto MMT AuroraTech

Bem-vindo ao repositório do Projeto MMT AuroraTech! Este projeto é uma aplicação web desenvolvida para demonstrar as funcionalidades de um servidor back-end integrado com um front-end interativo.

## Sobre o Projeto

  Nosso projeto é uma agência de vagas online dedicada exclusivamente a mulheres na área de Tecnologia da Informação (TI). Com o objetivo de promover a diversidade e a inclusão no setor, criamos uma plataforma intuitiva e segura onde mulheres talentosas podem encontrar oportunidades de emprego que correspondam às suas habilidades e aspirações. Nossa missão é facilitar a conexão entre candidatas e empresas comprometidas com a igualdade de gênero, oferecendo recursos de suporte, dicas de carreira e uma comunidade de apoio para empoderar mulheres em todas as fases de suas carreiras na TI.

## Passo a Passo para Rodar o Servidor

### 1. Clonar o Repositório

Primeiramente, clone o repositório do GitHub para sua máquina local:

```sh
git clone https://github.com/AlissonRayanss/Projeto-MMT-AuroraTech
```

### 2. Configurar o Banco de Dados

No MySQL Workbench, abra o arquivo Data base que está no repositório clonado e execute o código SQL contido nele para criar e popular o banco de dados necessário.
(mude a senha para a senha do seu workbench no arquivo "db-connection.ts" do vscode para ter acesso)

### 3. Iniciar o Servidor Back-End

Acesse a pasta do servidor back-end no Visual Studio Code (ou qualquer outro terminal de sua preferência) com o comando:

```sh
cd Projeto-MMT-AuroraTech/codigo-fonte/aurora-tech-server-main
```
Instale as dependências do projeto com o comando:

```sh
npm i
```
Inicie o servidor em modo de desenvolvimento com o comando:

```sh
npm run start:dev
```
### 4. Iniciar o Cliente Front-End

Em um novo terminal, acesse a pasta do cliente front-end com o comando:

```sh
cd Projeto-MMT-AuroraTech/codigo-fonte/aurora-tech-client-main
```
Instale as dependências do projeto com o comando:

```sh
npm i
```
Inicie o servidor do cliente com o comando:

```sh
npm run dev
```
### 5. Acessar a Aplicação

Assim que o servidor do cliente estiver rodando, um link localhost será gerado. Acesse esse link em seu navegador para visualizar o site do projeto
