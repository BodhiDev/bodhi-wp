# Bodhi Linux Website

## Development setup

The idea is to localize web development using `docker-compose`.
Download and install (docker)[https://docs.docker.com/engine/install/ubuntu/] and (docker-compose)[https://docs.docker.com/compose/install/] from their respective links.
`docker-compose up -d` will bring up a default install of wordpress for now, at `http://localhost:8080`.
Use `docker-compose down` to stop the services.
The wordpress files and db folder are under `${HOME}/bodhilinux/{wordpress|db}`, this will in the future made configurable.

## Todo
- Schema download for existing install from data store(s3? linux server?)
- Download all plugins.
- Download theme and css.
- Ensure local install boots.
