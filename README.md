# week10LCC

This repository contains a simple `n8n` setup for Docker and GitHub Codespaces.

## Run with Docker Compose

Start the service:

```bash
docker compose up -d
```

Then open n8n at:

```
http://localhost:5678
```

## Codespaces

The repository includes a `.devcontainer/devcontainer.json` file configured to start `n8n` automatically when the Codespace opens.

### Port forwarding

If the port is not forwarded automatically, forward `5678` in Codespaces to access the n8n UI.

## Files

- `docker-compose.yml` — defines the `n8n` service and persistent data volume
- `.devcontainer/devcontainer.json` — configures the Codespaces container to run `n8n`
