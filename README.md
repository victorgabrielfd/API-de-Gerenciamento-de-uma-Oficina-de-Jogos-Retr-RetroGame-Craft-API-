**# Guia de Estruturação: README.md Obrigatório

Este documento serve como modelo e instrução sobre o que deve conter em cada seção obrigatória do seu arquivo de documentação.

---

## Título + Descrição
> **O que deve conter aqui:** O nome claro do seu projeto no título principal (`#`). Logo abaixo, você deve explicar o que o seu projeto faz utilizando apenas **1 ou 2 frases**. Seja direto e objetivo, indicando o tema da sua API (ex: API de Gerenciamento de Aluguel de Carros, Sistema Escolar, etc).

---

## Como executar
> **O que deve conter aqui:** O passo a passo técnico e completo para que qualquer pessoa consiga rodar o seu projeto do zero no computador dela. É obrigatório listar e explicar a sequência exata de comandos no terminal:
>
> 1. Como clonar o repositório usando `git clone <link-do-seu-repositorio>`.
> 2. Como baixar as dependências do `node_modules` usando `npm install`.
> 3. Como colocar o servidor para rodar localmente usando `npm run dev`.

---

## Endpoints / Rotas
> **O que deve conter aqui:** Uma tabela Markdown organizada que mapeia a estrutura de comunicação da sua API. Cada linha da tabela precisa detalhar obrigatoriamente:
> *   O **Método HTTP** utilizado (`GET`, `POST`, `PUT`, `DELETE`).
> *   A **URL / Rota** exata do endpoint (ex: `/api/usuarios`, `/api/usuarios/:id`).
> *   A **Descrição** clara de qual ação aquela rota executa no sistema (ex: "Cadastra um novo usuário", "Busca dados por ID").

---

## Tecnologias usadas
> **O que deve conter aqui:** Uma lista com marcadores (`*`) indicando todas as ferramentas, ecossistemas e bibliotecas que dão sustentação ao código do seu projeto. Você deve listar itens fundamentais como:
> *   **Node.js** (Ambiente de execução)
> *   **TypeScript** (Linguagem com tipagem)
> *   **Express** (Framework de rotas)
> *   **EJS** (Motor de visualização das páginas)
> *   Qualquer outra biblioteca extra utilizada.

---

## Estrutura de pastas
> **O que deve conter aqui:** Uma representação visual em árvore de texto (usando caracteres de linhas) mostrando como os arquivos do seu projeto estão organizados fisicamente. É obrigatório demonstrar a separação das responsabilidades do padrão MVC dentro do diretório principal, indicando onde ficam:
> *   A pasta `src/` (Código fonte).
> *   As pastas internas `models/`, `controllers/`, `views/`, `routes/`.
> *   Os arquivos de configuração na raiz, como `package.json` e `tsconfig.json`.

---

##  Autor
*   **Nome:** Victor
*   **Turma:** 2A
*   **Instituição:** Senac**
