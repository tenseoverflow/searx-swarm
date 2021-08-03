# Searx config for my swarm servers

Add `MORTYKEY` (random string), `EMAIL` and `SEARXHOSTNAME` (your Searx instance hostname) environment values.

Deploy it via `docker stack deploy -c docker-compose.yml searx`.

For updating `settings.yml` (or `rules.json`) use `SETTINGS_TIMESTAMP=$(date +%s) docker stack deploy -c docker-compose.yml searx` for no downtime.
