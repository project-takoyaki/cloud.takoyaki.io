# cloud.takoyaki.io

Marketing website for Takoyaki Cloud.

## Deploy

```bash
git clone git@github.com:project-takoyaki/cloud.takoyaki.io.git
cd cloud.takoyaki.io
docker compose up -d --build
```

The site will be available on `127.0.0.1:3100`. Point a reverse proxy (nginx, caddy, etc.) at it.

## Rebuild after changes

```bash
git pull
docker compose up -d --build
```

## Development

```bash
bun install
bun run dev
```
