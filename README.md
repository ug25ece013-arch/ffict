# AI Ethics Analyzer (Render Ready)

This folder is a merged frontend + backend project prepared for direct GitHub and Render deployment.

## Structure

- `server.js` - Express backend and static hosting
- `public/index.html` - Frontend UI
- `routes/` and `utils/` - API logic
- `render.yaml` - Render service configuration

## Local Run

1. Install dependencies:
   - `npm install`
2. Create `.env` from `.env.example` and set `GEMINI_API_KEY`.
3. Start server:
   - `npm start`
4. Open:
   - `http://localhost:3000`

## Deploy to Render

1. Push this folder to a GitHub repository.
2. In Render, create a new Web Service from that repo.
3. Render will use `render.yaml` automatically.
4. Add environment variable:
   - `GEMINI_API_KEY`
5. Deploy.
