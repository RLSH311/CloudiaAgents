# Cloudia Agents

The purpose of this repo is to create a manifest (docker compose) for all the services required to run Cloudia-Agent.

It will deploy:
- Inventory Daemon
- Dumper Daemon
- Trash Deleter Daemon
- Redis - optional. Only one agent should run this, the rest connect to it