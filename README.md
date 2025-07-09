# NLW Agents

Projeto desenvolvido durante o evento **NLW (Next Level Week)** da Rocketseat, focado em criar uma aplicação web moderna com React e TypeScript.

## 🚀 Tecnologias Utilizadas

### Core
- **React 19** - Biblioteca para construção de interfaces
- **TypeScript** - Linguagem de programação tipada
- **Vite** - Build tool e dev server

### Styling & UI
- **Tailwind CSS 4** - Framework CSS utilitário
- **Radix UI** - Componentes acessíveis e customizáveis
- **Lucide React** - Ícones modernos
- **Class Variance Authority** - Sistema de variantes para componentes

### State Management & Data Fetching
- **TanStack Query** - Gerenciamento de estado do servidor e cache

### Routing
- **React Router DOM** - Roteamento client-side

### Development Tools
- **Biome** - Linter e formatter (substituindo ESLint + Prettier)
- **Ultracite** - Configuração de linting otimizada

## 📁 Estrutura do Projeto

```
src/
├── components/
│   └── ui/          # Componentes base (shadcn/ui style)
├── pages/           # Páginas da aplicação
├── lib/             # Utilitários e configurações
└── main.tsx         # Entry point
```

## 🛠️ Setup e Configuração

### Pré-requisitos
- Node.js (versão 18 ou superior)
- npm ou yarn

### Instalação

1. Clone o repositório:
```bash
git clone https://github.com/arthurlozano/nlw-agents-web.git
cd web
```

2. Instale as dependências:
```bash
npm install
```

3. Execute o projeto em modo de desenvolvimento:
```bash
npm run dev
```

4. Para build de produção:
```bash
npm run build
```

5. Para preview do build:
```bash
npm run preview
```

## 🎯 Funcionalidades

- Criação de salas
- Navegação entre páginas
- Interface responsiva e moderna
- Componentes reutilizáveis

## 📝 Padrões de Projeto

- **Componentes**: Utilização de componentes funcionais com TypeScript
- **Roteamento**: React Router para navegação SPA
- **Styling**: Tailwind CSS com classes utilitárias
- **State Management**: TanStack Query para dados do servidor
- **Code Quality**: Biome para linting e formatação automática

---

*Este README foi criado usando IA com o Cursor* 