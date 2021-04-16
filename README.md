# traefik
Local dev environment for php.

1. Clone repository inside root of your project.
2. Rename `env.text` to `.env`.
3. Change contents in `.env` file to suit your needs.
4. Go to `build/traefik` and run `start.sh`.
5. Go to root of your project (where `docker-compose.yml` file is).
6. Run `docker-compose up`.
7. Wait until your site is available at specified `PROJECT_HOSTNAME` in `.env` file.
