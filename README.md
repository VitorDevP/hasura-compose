# hasura-compose
Hasura docker compose

This repo contain docker compose with postgres and hasura configured

To run both containers, run command `docker compose up`

To run only hasura container and configure an external postgres db run `docker compose up hasura`, before run command, add correct environment values to .env file.

Run without .env file, Issue command `docker compose -e ADMIN_SECRET=SPICE_SECRET up`