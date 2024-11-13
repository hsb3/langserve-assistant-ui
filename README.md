# langserve-assistant-ui

This is an example of using LangServe to create a LangGraph agent that can be used in a FastAPI server, then streaming response to the UI with Nextjs Vercel AI SDK and [assistant-ui](https://www.assistant-ui.com/)

## How to run

### Backend

I use Python 3.11.
Backend is created with LangChain CLI.

```bash
cd backend
poetry install
poetry run python -m app.server
```

### Frontend

Frontend is created by `npx assistant-ui@latest create frontend`.

Node version: v20.18.0
Npm version: v10.9.2
Yarn version: v1.22.22

```bash
cd frontend
yarn install
yarn dev
```
