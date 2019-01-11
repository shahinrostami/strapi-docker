# strapi-docker
A docker-compose file for getting Strapi up and running with MariaDB/MySQL.


## Instructions

1. Download this repository as a ZIP or clone it `git clone https://github.com/shahinrostami/strapi-docker.git`;
2. Change into the directory `cd strapi-docker`;
3. Open `docker-compose.yml` in your editor and substitute `C:/srv/` with a directory on your host machine. This must be shared with Docker (check Docker preferences, especially on Windows);
4. Create the database and application containers using `docker-compose up -d`.
