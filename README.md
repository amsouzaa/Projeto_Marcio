# 🧠 Projeto Marcio

## 🎯 Objetivo

O Projeto Marcio é uma plataforma web desenvolvida para conscientização sobre fake news, suporte ao usuário e gestão de contas, integrando recursos de inteligência artificial, autenticação segura e arquitetura moderna.

O objetivo é oferecer uma experiência intuitiva, segura e escalável, promovendo o combate à desinformação e facilitando o acesso ao suporte.

## 🧰 Tecnologias Utilizadas

- **Back-end:**
  - FastAPI (Python)
  - Supabase (autenticação e banco de dados)
  - Uso da API do Groq console para integração com inteligência artificial
- **Front-end:**
  - Next.js (React)
  - TailwindCSS
- **Banco de Dados:**
  - Supabase (PostgreSQL)
- **Criptografia & Autenticação:**
  - JWT para autenticação segura e proteção de rotas
- **Inteligência Artificial:**
  - Uso de Chat-GPT e Copilot para auxílo de código
- **Arquitetura da Aplicação:**
  - Separação entre frontend (Next.js) e backend (FastAPI)
  - Comunicação via API REST
  - Autenticação baseada em JWT
  - Integração com Supabase para dados e autenticação

## 🏗️ Estrutura do Projeto

```
Projeto-Marcio/
├── backend/                  # API REST com FastAPI, rotas, autenticação, IA
├── frontend/                 # Interface web com Next.js
│   ├── src/
│   │   ├── app/             # Páginas (fake news, suporte, login, dashboard)
│   │   ├── components/      # Componentes reutilizáveis
│   │   └── contexts/        # Contextos globais (ex: autenticação)
└── README.md
```

# Frontend

Este README documenta apenas a parte do frontend do "Projeto Marcio" e, em particular, descreve a minha contribuição feita este trabalho.

Resumo da contribuição (escopo do autor)

- Tela de Login (página de autenticação): `src/app/login/page.js` (e componentes relacionados).
- Landing page / página inicial: `src/app/page.js`.
- Alteração do layout principal do aplicativo: `src/app/layout.js` e `src/components/layout.js`.
- Criação da sidebar (barra lateral): `src/components/app-sidebar.js` e/ou `src/components/ui/sidebar.jsx`.

Essas alterações/implementações são a parte do frontend que o autor desenvolveu — o backend (FastAPI) e outras partes do projeto foram desenvolvidas por outros membros.

## Visão geral do frontend

- Framework: Next.js (React)
- Estilização: TailwindCSS (configuração presente entre dependências)
- Padrões: a aplicação usa a pasta `src/app` (App Router) para páginas e `src/components` para componentes reutilizáveis.
