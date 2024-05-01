# wiremock-compose
Start Wiremock via docker-compose (instead of remembering the run command)

## Configuration

To modify the port in which Wiremock listens on, edit the PORT environment variable in the `.env` file.

## Running

To run the docker-compose file, run the following command: `docker-compose up -d` (docker-compose is required for this to work)

`docker compose up -d` may work depending on your preferred Docker runtime.
