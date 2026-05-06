# app.tofs.se

Animerad landningssida för app.tofs.se, servad via nginx i Docker.

## Köra lokalt

```bash
docker compose up -d
```

Öppna `http://localhost:3011` i webbläsaren.

## Deploya på VPS

```bash
git clone https://github.com/jimand/app.tofs.se.git
cd app.tofs.se
docker compose up -d
```

Peka Nginx Proxy Manager mot `localhost:3011`.

## Uppdatera

```bash
git pull && docker compose up -d --build
```
