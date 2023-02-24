# Traefik

## Setup

- `cp .env.example .env`
- adjust values
- `EMAIL` - for letsencrypt
- `TRAEFIK_PASSWORD_HASH` output of `openssl passwd -apr1 | sed -E "s:[\$]:\$\$:g"`
- `docker compose up -d` or `docker-compose up -d` - depends of docker version
