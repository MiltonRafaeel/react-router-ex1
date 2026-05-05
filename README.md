# Rotas (Exercício 1) — React Router DOM

Projeto simples feito em **React + TypeScript + Vite** para praticar **rotas** e **links** com **react-router-dom**, seguindo o layout do Figma do exercício.

## Links

- Repositório: [MiltonRafaeel/react-router-ex1](https://github.com/MiltonRafaeel/react-router-ex1)
- Figma (layout): [Rotas-Exercicio1](https://www.figma.com/file/c1bcLS6WcZUxWVigd4DCGN/Rotas-Exercicio1)

> Observação: o link do Figma pode exigir permissão/login para visualizar.

## Objetivo do projeto

- Praticar navegação entre páginas com `Link`
- Entender **rotas aninhadas** (layout com `<Outlet />`)
- Reforçar organização de componentes e CSS básico

## Rotas implementadas

As rotas são definidas em `src/App.tsx` usando `BrowserRouter`, `Routes` e `Route`:

| Rota | Componente | Descrição |
|------|------------|-----------|
| `/` | `Home` + `HomeBody` (index) | Página inicial |
| `/promotion` | `Home` + `Promotion` | Página de promoção |
| `/sub` | `Home` + `Subscription` | Página de inscrição |

O componente `Home` funciona como **layout base**, renderizando o `Header` e um `<Outlet />` para o conteúdo da rota filha.

## Stack utilizada

- React (`react` / `react-dom`)
- TypeScript
- Vite
- React Router DOM (`react-router-dom@6.4.1`)
- Yarn
- ESLint
- CSS

## Como executar (Yarn)

```bash
# 1) Clone o repositório
git clone https://github.com/MiltonRafaeel/react-router-ex1.git

# 2) Acesse a pasta
cd react-router-ex1

# 3) Instale as dependências
yarn

# 4) Rode o projeto
yarn dev
