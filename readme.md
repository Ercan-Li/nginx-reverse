# Reverse nginx proxy

Most of Ercan-Li projects will make use of this as an entrypoint into other Docker set ups (using the same network name `nginx-proxy`). 

First, run `docker network ls`. If you don’t see a network called `nginx-proxy`, run this command: `docker network create nginx-proxy`. 

Then run `docker compose up -d` in this directory.