# API-Teste-GLOCK

Uma API simples de Hello World criada com Node.js e Express.

## Descrição

Este é um projeto de API REST básica que retorna uma mensagem "Hello World!" em formato JSON.

## Pré-requisitos

- Node.js (versão 12 ou superior)
- npm (Node Package Manager)

## Instalação

1. Clone este repositório:
```bash
git clone https://github.com/dyfreire/API-Teste-GLOCK.git
cd API-Teste-GLOCK
```

2. Instale as dependências:
```bash
npm install
```

## Como Executar

Para iniciar o servidor, execute:

```bash
npm start
```

O servidor será iniciado na porta 3000 (ou na porta definida pela variável de ambiente PORT).

## Uso

Após iniciar o servidor, acesse:

```
http://localhost:3000/
```

A resposta será:

```json
{
  "message": "Hello World!"
}
```

## Estrutura do Projeto

- `server.js` - Arquivo principal da aplicação
- `package.json` - Configurações e dependências do projeto
- `README.md` - Documentação do projeto

## Tecnologias Utilizadas

- Node.js
- Express.js

## Licença

Este projeto é de código aberto e está disponível para uso livre.
