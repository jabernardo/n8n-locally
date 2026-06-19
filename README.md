# Local Setup for n8n

## Pre-requisites

1. [Docker](https://www.docker.com/get-started/)
2. [ngrok](https://dashboard.ngrok.com/get-started/setup/linux)

## Environment setup

1. Get your URL from ngrok by running `ngrok http 5678`
2. Edit `N8N_HOST` with `ngrok` URL in [docker-compose.yml](./docker-compose.yml)

## Open n8n

- Complete setup on n8n dashboard
