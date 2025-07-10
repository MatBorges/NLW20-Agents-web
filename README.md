# NLW Agents

Projeto desenvolvido durante o evento **NLW** da Rocketseat.

## Descrição

O NLW Agents é uma aplicação fullstack composta por backend em Node.js (Fastify) e frontend em React, utilizando TypeScript e ferramentas modernas para produtividade e qualidade de código.

---

## Tecnologias Utilizadas

### Backend (`server/`)
- **Node.js** + **TypeScript**
- **Fastify**: Framework web rápido.
- **Zod**: Validação de esquemas e variáveis de ambiente.
- **Drizzle ORM**: ORM para bancos SQL.
- **PostgreSQL**: Banco de dados relacional.
- **drizzle-seed**: Geração de dados fake.
- **@fastify/cors**: Suporte a CORS.
- **fastify-type-provider-zod**: Integração de validação com Zod.

**Padrões de Projeto**
- Organização por domínio: `db/`, `http/routes/`, `env.ts`.
- Validação centralizada de variáveis de ambiente.
- Uso de migrations e seeds.
- Tipagem e validação de rotas com Zod.

---

### Frontend (`web/`)
- **React 19** + **TypeScript**
- **Vite**: Bundler e dev server.
- **React Router DOM**: Rotas SPA.
- **@tanstack/react-query**: Gerenciamento de dados assíncronos.
- **Tailwind CSS**: Utilitários CSS.
- **class-variance-authority**, **clsx**, **tailwind-merge**: Composição de classes CSS.
- **Radix UI**: Componentes acessíveis.
- **lucide-react**: Ícones SVG.

**Padrões de Projeto**
- Organização por domínio: `components/`, `pages/`, `lib/`.
- Hooks para dados e lógica.
- Componentização e reutilização de UI.
- Estilização com Tailwind CSS.

---

## Como rodar

1. **Backend**
   - Instale dependências: `npm install`
   - Configure `.env` conforme `.env.example`
   - Suba o banco: `docker-compose up -d`
   - Rode migrations/seeds se necessário
   - Inicie: `npm run dev`

2. **Frontend**
   - Instale dependências: `npm install`
   - Inicie: `npm run dev`

---

Projeto em desenvolvimento durante o evento NLW da Rocketseat.