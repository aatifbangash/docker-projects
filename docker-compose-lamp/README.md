This is a basic LAMP stack environment built using Docker Compose. It consists following:

* PHP
* Apache
* MySQL
* phpMyAdmin

## Installation

Clone this repository on your local computer and checkout the appropriate branch e.g. 7.1.x. Run the `docker-compose up -d`.

```shell
git clone https://github.com/sprintcube/docker-compose-lamp.git
cd docker-compose-lamp/
git fetch --all
git checkout 7.1.x
docker-compose up -d
```

Your LAMP stack is now ready!! You can access it via `http://localhost`.

