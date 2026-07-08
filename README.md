# Backend - Wassala AI V1

## Instalar
```bash
pip install -r requirements.txt
uvicorn app.main:app --reload
```

Servidor:
- http://127.0.0.1:8000
- Docs: http://127.0.0.1:8000/docs

## Endpoint principal
POST `/analyze-chart`

Campos:
- `file`: imagem do gráfico
- `asset`: ex. XAUUSD
- `timeframe`: ex. M15