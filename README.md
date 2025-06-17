# N8N Docker Setup

This repository contains a Docker-based setup for running [n8n](https://n8n.io/), a workflow automation tool.

## Prerequisites

- Docker
- Docker Compose

## Getting Started

1. Clone this repository
2. Configure environment variables in `.env` file
3. Start n8n using Docker Compose:
   ```bash
   docker-compose up -d
   ```

The n8n instance will be available at `http://localhost:5678` (default port).

## Environment Variables

Environment configuration is stored in the `.env` file. See the [n8n environment variables documentation](https://docs.n8n.io/hosting/environment-variables/) for all available options.

## Stopping n8n

To stop the n8n instance:
```bash
docker-compose down
```

## Backup

Remember to regularly backup your n8n data. The workflows and credentials are stored in the configured database.
