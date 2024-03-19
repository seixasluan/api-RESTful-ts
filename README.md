# API RESTful em TypeScript

Este é um projeto de exemplo de uma API RESTful desenvolvida em TypeScript.

## Descrição

Esta API foi desenvolvida com o intuito de fornecer um exemplo de implementação de uma API RESTful usando TypeScript. Ela inclui operações básicas de CRUD (Criar, Ler, Atualizar, Deletar) para uma entidade fictícia.

## Funcionalidades

- **CRUD:** Operações básicas de criar, ler, atualizar e deletar para a entidade principal.
- **Validação de dados:** Utilização de middleware para validação de dados de entrada.
- **Persistência de dados:** Utilização de uma camada de dados para persistência em memória.

## Tecnologias Utilizadas

- TypeScript
- Node.js
- Express.js
- Eslint (para linting)
- Prettier (para formatação de código)

## Estrutura do Projeto

A estrutura do projeto é organizada da seguinte forma:

- **`src/`:** Contém o código-fonte da aplicação.
  - **`controllers/`:** Controladores da API.
  - **`middlewares/`:** Middlewares para validação de dados.
  - **`routes/`:** Definição das rotas da API.
  - **`services/`:** Lógica de negócio da aplicação.
  - **`utils/`:** Utilitários diversos.
- **`config/`:** Configurações da aplicação.

## Instalação

1. Clone este repositório.
2. Certifique-se de ter o Node.js instalado.
3. Instale as dependências com o comando `npm install`.
4. Inicie o servidor com `npm start`.

## Uso

- Acesse as rotas definidas na API através dos endpoints correspondentes.
- Consulte a documentação da API para obter mais detalhes sobre as operações disponíveis.

## Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir um problema para relatar bugs ou propor novas funcionalidades. Se desejar contribuir com código, por favor, abra uma PR (pull request).

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

Esse README serve como um guia básico para entender o projeto e como utilizá-lo.
