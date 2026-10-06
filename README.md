# Citas

Microservicio académico para la práctica de API Gateway.

## Endpoint principal
`/citas`

## Render
Build Command:
`pip install -r requirements.txt`

Start Command:
`gunicorn app:app`

## Endpoints
- GET `/`
- GET `/health`
- GET `/citas`
- GET `/citas/<id>`
- POST `/citas`

Los datos se almacenan en memoria y se reinician cuando el servicio vuelve a desplegarse o reinicia.
