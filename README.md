# Wordpress Docker
Contains a Docker Compose file for quickly starting a lightweight local Wordpress development environment.

Creates 3 containers:
- MySQL DB
- Wordpress
- WP CLI

Spins up a WP CLI container which can be accessed using `docker-compose run --rm cli bash`, and mounts a volume for access to WP files.
