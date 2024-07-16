# Fastify TypeScript Template

Este é um template para criar APIs utilizando Fastify com TypeScript. Ele já vem configurado com autoload de rotas, documentação Swagger e reinicialização automática usando `tsx`.

## Pré-requisitos

- Node.js v14 ou superior
- npm

## Instalação

1. Clone o repositório:

    ```bash
    git clone https://github.com/gabriel-codart/FastifyAPI.git

2. Navegue até o diretório do projeto:

    ```bash
    cd fastify-template

3. Instale as dependências:

    ```bash
    npm install

## Desenvolvimento

Para iniciar o servidor em modo de desenvolvimento com reinicialização automática, utilize o comando:

    ```bash
    npm run dev

O servidor será iniciado em http://localhost:2020 e a documentação Swagger estará disponível em http://localhost:2020/docs.

## Estrutura do Projeto

    ```plaintext
    src
  ├── controllers
  │   └── itemsController.ts  # Controladores para manipulação de lógica de negócios
  ├── models
  │   └── item.ts             # Modelos de dados
  ├── routes
  │   └── items.ts            # Definição das rotas
  └── index.ts                # Configuração principal do Fastify

## Documentação

Este template inclui a configuração do Swagger para documentação automática da API. Acesse a documentação em http://localhost:2020/docs.

## Contribuição

Sinta-se à vontade para fazer um fork do projeto e enviar pull requests. Sugestões e melhorias são sempre bem-vindas!

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.