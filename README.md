# RetroGame Craft API

A **RetroGame Craft API** é um sistema completo para o gerenciamento de oficinas especializadas na manutenção, restauração e customização de consoles de videogame clássicos. A aplicação permite controlar o inventário de peças raras, gerenciar ordens de serviço e visualizar o status dos reparos através de uma interface web dinâmica.

---

## Tecnologias Usadas

O projeto foi desenvolvido utilizando as seguintes ferramentas e tecnologias:

*   **Node.js**: Ambiente de execução para o JavaScript no backend.
*   **TypeScript**: Superconjunto do JavaScript que adiciona tipagem estática ao código.
*   **Express**: Framework web rápido e minimalista para criação das rotas e APIs.
*   **EJS (Embedded JavaScript templates)**: Motor de visualização para renderizar páginas HTML dinâmicas no servidor.
*   **ts-node-dev**: Ferramenta de desenvolvimento para reiniciar o servidor automaticamente a cada alteração.

---

## Estrutura de Pastas

A arquitetura do projeto segue o padrão MVC (Model-View-Controller) para manter a separação clara de responsabilidades:

```text
├── src/
│   ├── controllers/   # Regras de negócio e controle das requisições e respostas
│   ├── models/        # Estruturas de dados, interfaces e tipos do TypeScript
│   ├── routes/        # Definição dos endpoints da API e rotas das páginas
│   ├── views/         # Arquivos de template EJS para a interface do usuário
│   └── server.ts      # Ponto de entrada do projeto e configuração do Express
├── package.json       # Gerenciamento de dependências e scripts do projeto
└── tsconfig.json      # Configurações do compilador TypeScript
