# Cloudia Agents

## Description

The purpose of this repo is to create a manifest (docker compose) for all the services required to run Cloudia-Agent.

It will deploy:
- Inventory Daemon
- Dumper Daemon
- Trash Deleter Daemon
- Redis - optional. Only one agent should run this, the rest connect to it

## Running

Use a custom env file:

```
docker compose --env-file .env.dev up -d
```

Or rename `.env.dev` to `.env` and run:

```
docker compose up -d
```