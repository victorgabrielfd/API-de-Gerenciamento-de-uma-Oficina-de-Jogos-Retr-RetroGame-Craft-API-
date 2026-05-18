# RetroGame Craft API

A **RetroGame Craft API** é uma aplicação backend desenvolvida para gerenciar uma oficina completa de manutenção, restauração e customização de consoles de videogame clássicos. O sistema permite o controle total de ordens de serviço, inventário de peças e o acompanhamento dos reparos por meio de uma interface web dinâmica.

---

## Tecnologias Usadas

O projeto foi construído utilizando as seguintes ferramentas e tecnologias:

*   **Node.js**: Ambiente de execução para rodar o JavaScript no servidor.
*   **TypeScript**: Superconjunto do JavaScript que adiciona tipagem estática e segurança ao código.
*   **Express**: Framework web minimalista utilizado para gerenciar as rotas e requisições HTTP.
*   **EJS (Embedded JavaScript templates)**: Motor de visualização utilizado para renderizar páginas HTML dinâmicas diretamente do servidor.
*   **ts-node-dev**: Ferramenta de desenvolvimento para reiniciar o servidor automaticamente a cada alteração.

---

## Estrutura de Pastas

A arquitetura do projeto segue o padrão MVC (Model-View-Controller) para garantir a separação de responsabilidades e organização do código:

```text
├── src/
│   ├── controllers/   # Controladores: Contêm as regras de negócio e manipulação de requisições/respostas
│   ├── models/        # Modelos: Definição das estruturas de dados e interfaces do TypeScript
│   ├── routes/        # Rotas: Definição dos endpoints e caminhos da aplicação
│   ├── views/         # Visualizações: Arquivos de template EJS para a interface do usuário
│   └── server.ts      # Ponto de entrada do projeto e configuração do servidor Express
├── package.json       # Gerenciamento de dependências, pacotes e scripts do projeto
└── tsconfig.json      # Configurações de compilação do TypeScript
