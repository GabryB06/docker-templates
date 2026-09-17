
# Docker templates

This repository contains a collection of Docker templates for various applications

## Quick start

1. Clone this repository
2. Navigate to the desired template directory
3. Build and run the Docker container with `docker compose up --build`

## Containers list

- Apache with PHP module
  - Apache all in one ([More informations](apache/apache_all_in_one/README.md))
  - Apache with no cache
  - Apache with no cache and with custom 404 page
  - Apache with MariaDB and PhpMyAdmin
- MariaDB
- MySQL
- PhpMyAdmin as compose override (put it in the same directory as the DB's docker-compose.yml and change the `PMA_HOST` variable)
