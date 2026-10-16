# Clarity AI

A writing assistant frontend backed by a FastAPI application architecture.

## Project structure

- `frontend/` — static HTML/CSS/JS app
- `backend/` — FastAPI backend service
- `backend/app/` — application package
- `backend/app/api/` — API routes
- `backend/app/core/` — configuration and auth helpers

## Run the backend

```bash
cd backend
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
uvicorn app.main:app --reload --host 0.0.0.0 --port 5000
```

Then open the app in a browser at:

-file:///C:/Users/sahil/AppData/Local/Temp/309b47e2-db23-479c-9290-e3199813a909_website-ac71273d-c92f-4ff3-88f1-c517e7656d0a.zip.909/index.html

## Architecture

Frontend → FastAPI → AI API / Database / Auth
