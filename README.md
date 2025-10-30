CompreAqui Frontend (React + Vite)

1. Instalar dependências:
   npm install

2. Rodar em desenvolvimento:
   npm run dev

3. Colocar variáveis no arquivo `.env` (crie a partir de .env.example):
   VITE_API_URL=https://seu-backend-url.com
   VITE_GOOGLE_CLIENT_ID=SEU_CLIENT_ID_GOOGLE

Observações:
- Este frontend usa Google Identity Services para login com Google. O backend deve expor /api/google-login para trocar o token Google por JWT do sistema.
