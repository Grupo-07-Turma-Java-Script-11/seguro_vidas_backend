# 🛡️ Seguro Vida — Sistema de Seguro de Vidas

> Projeto Integrador 2 — Grupo 07 | Turma JavaScript 11 | Generation Brasil

---

## 📋 Descrição

O **Seguro Vida** é uma aplicação backend desenvolvida como Projeto Integrador da [Generation Brasil](https://brazil.generation.org/), com o objetivo de simular um sistema de gestão de seguros de vida. O sistema permite o gerenciamento de apólices, beneficiários e demais entidades relacionadas ao domínio de seguros.

A aplicação foi construída com **NestJS** e **TypeScript**, seguindo os princípios de arquitetura modular, separação de responsabilidades e boas práticas de desenvolvimento de APIs RESTful.

---

## 🚀 Tecnologias Utilizadas

| Tecnologia | Descrição |
|---|---|
| [Node.js](https://nodejs.org/) | Ambiente de execução JavaScript server-side |
| [NestJS](https://nestjs.com/) | Framework progressivo para aplicações Node.js |
| [TypeScript](https://www.typescriptlang.org/) | Superset tipado do JavaScript |
| [ESLint](https://eslint.org/) | Linter para padronização de código |
| [Prettier](https://prettier.io/) | Formatador de código |
| [Jest](https://jestjs.io/) | Framework de testes |

---

## 📁 Estrutura do Projeto

```
seguro_vida/
├── src/                  # Código-fonte principal da aplicação
│   ├── app.module.ts     # Módulo raiz da aplicação
│   ├── app.controller.ts # Controller principal
│   ├── app.service.ts    # Service principal
│   └── main.ts           # Ponto de entrada da aplicação
├── test/                 # Testes automatizados (e2e)
├── .gitignore
├── .prettierrc           # Configuração do Prettier
├── eslint.config.mjs     # Configuração do ESLint
├── nest-cli.json         # Configuração do NestJS CLI
├── package.json
├── tsconfig.json         # Configuração do TypeScript
└── tsconfig.build.json
```

---

## ⚙️ Pré-requisitos

Antes de começar, certifique-se de ter instalado:

- [Node.js](https://nodejs.org/) (versão 18 ou superior)
- [npm](https://www.npmjs.com/) (geralmente incluído com o Node.js)
- [Git](https://git-scm.com/)

---

## 🔧 Instalação e Configuração

### 1. Clone o repositório

```bash
git clone https://github.com/Grupo-07-Turma-Java-Script-11/seguro_vida.git
```

### 2. Acesse o diretório do projeto

```bash
cd seguro_vida
```

### 3. Instale as dependências

```bash
npm install
```

---

## ▶️ Executando a Aplicação

```bash
# Modo desenvolvimento
npm run start

# Modo watch (reinicia automaticamente ao detectar mudanças)
npm run start:dev

# Modo produção
npm run start:prod
```

A aplicação estará disponível em: **`http://localhost:3000`**

---

## 🧪 Executando os Testes

```bash
# Testes unitários
npm run test

# Testes end-to-end (e2e)
npm run test:e2e

# Cobertura de testes
npm run test:cov
```

---

## 🌐 Endpoints da API

A API segue o padrão RESTful. Após iniciar a aplicação, acesse `http://localhost:3000` para visualizar os endpoints disponíveis.

---

## 👥 Equipe

Desenvolvido pelo **Grupo 07** da Turma JavaScript 11 da [Generation Brasil](https://brazil.generation.org/).

| Integrante | GitHub |
|---|---|
| Grupo 07 | [@Grupo-07-Turma-Java-Script-11](https://github.com/Grupo-07-Turma-Java-Script-11) |

---

## 📄 Licença

Este projeto foi desenvolvido para fins educacionais como parte do programa da **Generation Brasil**.

---

## 🔗 Links Úteis

- [Documentação NestJS](https://docs.nestjs.com/)
- [Generation Brasil](https://brazil.generation.org/)
- [Repositório no GitHub](https://github.com/Grupo-07-Turma-Java-Script-11/seguro_vida)
