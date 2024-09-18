# Projeto de Agenda

Este projeto é uma aplicação de agenda simples, onde os usuários podem se cadastrar, fazer login, criar, editar e deletar contatos de sua agenda pessoal. O projeto utiliza tecnologias como Node.js, Express, MongoDB e EJS. No projeto utilizei o modelo de arquitetura MVC (Models, views e controllers).

## Funcionalidades

- Cadastro de usuários
- Login de usuários
- Criação, edição e exclusão de contatos
- Mensagens de sucesso e erro com Flash Messages
- Proteção de formulários com CSRF Tokens

## Tecnologias Utilizadas

- **Node.js**: Ambiente de execução JavaScript no servidor
- **Express**: Framework web para Node.js
- **MongoDB**: Banco de dados NoSQL
- **Mongoose**: ODM para MongoDB
- **EJS**: Motor de templates para renderização no servidor
- **CSRF Protection**: Proteção contra ataques CSRF
- **Express Session**: Gerenciamento de sessões de usuário
- **Connect-Mongo**: Armazenamento de sessões no MongoDB
- **Flash Messages**: Exibição de mensagens de feedback para o usuário

## Requisitos

- **Node.js** versão 14 ou superior
- **MongoDB** versão 4.0 ou superior

## Instalação

1. Clone o repositório para o seu ambiente local:
```bash
   git clone https://github.com/seu-usuario/projeto-agenda.git
```

2. Acesse a pasta do projeto:
```bash
    cd projeto-agenda
```

3.Instale as dependências:
```bash
    npm install
```

4. Configure o arquivo .env:

Crie um arquivo .env na raiz do projeto.
Adicione a string de conexão do MongoDB ao arquivo .env

```bash
    CONNECTIONSTRING=mongodb://seu-usuario:senha@localhost:27017/sua-agenda
```

## Executando o Projeto
Certifique-se de que o MongoDB está rodando.

Inicie o servidor:
```bash
npm start
```

Acesse a aplicação em: http://localhost:3000.





Tela de login:

![image](https://github.com/user-attachments/assets/cf778dac-5a36-4c86-ba1e-510e2776c391)



Tela dos contatos registrados:

![image](https://github.com/user-attachments/assets/852eb093-d338-4ff7-955a-33e2d52fc849)

