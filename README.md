# Rural Healthcare AI

Offline-first multimodal AI assistant for rural healthcare documentation.

## Project structure

- `frontend/` — React application
- `backend/` — Node.js and Express API
- `README.md` — project documentation

## Backend setup

```bash
cd backend
npm init -y
npm install express cors dotenv
npm install --save-dev nodemon
npm run dev
```

Create a `.env` file in `backend/`:

```env
PORT=5000
```

Open `http://localhost:5000` to test the API.

## Frontend setup

Create the React app with Vite inside `frontend/`:

```bash
cd frontend
npm create vite@latest . -- --template react
npm install
npm install axios react-router-dom dexie
npm run dev
```

Note: Vite may ask whether to overwrite existing files. Keep the provided `src/App.jsx` if you want to retain the starter screen, or restore it after scaffolding.
