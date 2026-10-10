# hellow-world

Minimal Nginx hello-world container for a Coolify and Cloudflare Tunnel smoke test.

## Local check

```bash
docker compose up --build
```

The container intentionally has no published host port. In Coolify, expose service port `80` through the Coolify proxy; Cloudflare Tunnel should route only to that proxy.
