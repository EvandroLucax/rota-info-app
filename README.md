
# Rota-Info App

## 1. Sobre o projeto

O Rota-Info App é um sistema desenvolvido para facilitar o acompanhamento do transporte escolar.

O projeto surgiu devido à falta de informações atualizadas sobre a localização dos ônibus, horários, atrasos e possíveis problemas durante as viagens.

O sistema permitirá que alunos e responsáveis consultem informações sobre os dois ônibus escolares, suas respectivas rotas e horários de funcionamento. Também será possível receber avisos sobre atrasos, problemas mecânicos e cancelamentos de viagens.

## 2. Integrantes da equipe

- Integrante 1 - Christiano Caragiu 
- Integrante 2 - Evandro Lucas 
- Integrante 3 - Luis Davi 
- Integrante 4 - Jose Fabricio 

## 3. Tecnologias utilizadas

- Linguagem: JavaScript
- Ambiente de execução: Node.js
- Framework: Express
- Templates: EJS
- Estilização: HTML, CSS e Bootstrap 5
- Banco de dados: MySQL
- Gerenciador do banco: MySQL Workbench
- Versionamento: Git e GitHub

## 4. Organização do projeto (MVC)

O projeto utiliza o padrão MVC (Model, View e Controller), separando as responsabilidades do sistema.

### Model
Responsável pelo acesso ao banco de dados e pelas operações com as informações.

Arquivos ficam na pasta `models/`.

### View
Responsável pelas telas e pela apresentação das informações ao usuário.

Arquivos ficam na pasta `views/`.

### Controller
Responsável por receber as ações dos usuários, chamar os Models e controlar as respostas do sistema.

Arquivos ficam na pasta `controllers/`.

### Outras pastas e arquivos

- `config/`: configurações do sistema e conexão com o banco de dados.
- `routes/`: definição das rotas de acesso às páginas e funcionalidades.
- `public/`: arquivos CSS, JavaScript do navegador e imagens.
- `app.js`: arquivo principal responsável por iniciar o servidor.
- `package.json`: informações e dependências do projeto.

## 5. Como instalar e executar o projeto

### Pré-requisitos

- Node.js instalado.
- MySQL instalado.
- MySQL Workbench instalado.
- Visual Studio Code ou outro editor de código.

### Instalação

1. Baixe ou clone o repositório do projeto.
2. Abra a pasta do projeto no terminal.
3. Instale as dependências com o comando:

npm install

### Configuração do banco de dados

1. Abra o MySQL Workbench.
2. Crie o banco de dados do projeto.
3. Configure os dados de conexão no arquivo `config/database.js`.

### Executando o projeto

No terminal, execute:

node app.js

Depois, abra o navegador e acesse:

http://localhost:3000

## 6. Objetivo

O objetivo do Rota-Info App é melhorar a comunicação entre os responsáveis pelo transporte escolar, os alunos e seus familiares, oferecendo informações mais rápidas e acessíveis sobre as viagens.
