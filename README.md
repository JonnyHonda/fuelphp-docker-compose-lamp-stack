# LAMP stack built with Docker Compose

This is a basic LAMP stack environment built using Docker Compose. It consists following:

* PHP 7.2
* Apache 2.4
* MySQL 5.7
* phpMyAdmin

As of now, we have 3 different branches for different PHP versions. Use appropriate branch as per your php version need:
* [5.6.x](https://github.com/sprintcube/docker-compose-lamp/tree/5.6.x)
* [7.1.x](https://github.com/sprintcube/docker-compose-lamp/tree/7.1.x)
* [7.2.x](https://github.com/sprintcube/docker-compose-lamp/tree/7.2.x)

## Installation

Clone this repository on your local computer and switch to branch `7.2.x`. Run the `docker-compose up -d`.

```shell
git clone https://github.com/sprintcube/docker-compose-lamp.git
cd docker-compose-lamp/
git fetch --all
git checkout 7.2.x
docker-compose up -d
```

Your LAMP stack is now ready!! You can access it via `http://localhost`.

## Configuration and Usage

Please read from appropriate version branch.
