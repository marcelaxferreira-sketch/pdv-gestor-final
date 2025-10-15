# PDV Gestor - Sistema de Ponto de Venda

Este é um sistema de Ponto de Venda (PDV) completo, criado com Node.js (backend) e React (frontend).

## Estrutura do Projeto

- `/backend`: Contém a API Node.js, o banco de dados SQLite e toda a lógica de negócio.
- `/frontend`: Contém a aplicação React, que é a interface visual do sistema.

## Como Publicar (Deploy)

### Backend (Render.com)

1. Crie um "New Web Service" no Render.
2. Conecte este repositório do GitHub.
3. Configure:
   - **Root Directory:** `backend`
   - **Build Command:** `npm install`
   - **Start Command:** `npm start`
4. Copie a URL gerada pelo Render (ex: `https://meu-pdv-backend.onrender.com`).

### Frontend (Vercel)

1. Importe este repositório do GitHub na Vercel.
2. Configure:
   - **Framework Preset:** `Vite`
   - **Root Directory:** `frontend`
3. **Importante:** Antes de fazer o deploy, vá em "Environment Variables" e crie uma variável chamada `VITE_API_URL` com a URL do seu backend do Render.
4. Faça o deploy.

Após esses passos, seu sistema estará no ar!

