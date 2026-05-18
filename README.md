# RetroGame Craft API

A **RetroGame Craft API** é uma solução backend desenvolvida para gerenciar oficinas especializadas na manutenção, restauração e modificação de consoles de videogame clássicos (como *NES, Master System, Mega Drive, Playstation 1*, entre outros). 

A API permite controlar o fluxo de ordens de serviço, gerenciar o estoque de peças de reposição raras e manter um histórico detalhado de customizações (como instalações de mods de vídeo HDMI, recaps de capacitores e reparos de carcaça).

---

## Tecnologias Utilizadas

*   **Ambiente de Execução:** [Node.js](https://nodejs.org/)
*   **Linguagem:** [TypeScript](https://www.typescriptlang.org/)
*   **Framework Web:** [Express](https://expressjs.com/)
*   **Ferramentas de Desenvolvimento:** `ts-node-dev` (recarregamento automático)

---

## Arquitetura e Estrutura do Projeto

O projeto segue o padrão arquitetural focado em separação de responsabilidades (Rotas, Controladores e Serviços/Repositórios):

```text
├── src/
│   ├── controllers/   # Regras de extração de dados da requisição e resposta HTTP
│   ├── models/        # Definição das estruturas de dados (Interfaces/Tipos)
│   ├── routes/        # Definição dos endpoints da API
│   ├── services/      # Regras de negócio e manipulação dos dados (CRUD)
│   └── server.ts      # Ponto de entrada e configuração do Express
├── package.json
└── tsconfig.json
