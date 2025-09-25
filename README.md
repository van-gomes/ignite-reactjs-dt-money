# Ignite ReactJS - DT Money

Aplicação desenvolvida durante o curso Ignite da Rocketseat, com foco em **ReactJS** e **boas práticas modernas de desenvolvimento frontend**.  
O projeto consiste em uma aplicação de controle financeiro que permite registrar transações de entrada e saída, visualizar listagens e consultar o saldo total.

---

## Tecnologias

- **ReactJS**
- **Vite** (bundler)
- **TypeScript**
- **Styled Components**
- **Radix UI** (componentes acessíveis)
- **Axios** (requisições HTTP)
- **Context API + Hooks**

---

## Funcionalidades

- Cadastro de novas transações (entradas e saídas).
- Listagem de todas as transações cadastradas.
- Resumo do balanço financeiro (entradas, saídas e total).
- Consumo de dados via API simulada com **JSON Server**.
- Estilização com **styled-components**.
- Componentização e boas práticas de organização de código.

---

## Instalação e uso

Clone o repositório:

```bash
git clone https://github.com/seu-usuario/ignite-reactjs-dt-money.git
cd ignite-reactjs-dt-money
```

Instale as dependências:

```bash
npm install
```

Inicie a aplicação e o servidor fake de API:

```bash
npm run dev
npm run dev:server
```

Abra no navegador:

```
http://localhost:5173
```

---

## Lint e formatação de código

O projeto utiliza ESLint integrado ao Prettier para garantir padronização do código.

Para verificar problemas de lint:

```bash
npm run lint
```

Para corrigir automaticamente problemas de formatação:

```bash
npm run lint:fix
```

Observação: a regra @typescript-eslint/no-empty-object-type foi desativada no projeto para manter compatibilidade entre versões do ESLint e TypeScript.

---

## Licença

Este projeto foi desenvolvido como parte do **Ignite da Rocketseat** e é de uso livre para estudos e melhorias pessoais.
