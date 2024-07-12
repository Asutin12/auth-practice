## Getting started (for development)
on your Docker host.

```bash
cp .env.sample .env
docker compose up -d --build   # up detached mode containers with build process.
docker compose down   # down containers.
```