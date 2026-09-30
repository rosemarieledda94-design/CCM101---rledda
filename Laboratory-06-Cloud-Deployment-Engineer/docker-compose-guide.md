Docker Compose Guide
What does the services: block do?

The services: block defines the containers that will be created and managed by Docker Compose. In this project, it contains two services: the database service using MariaDB and the app service using Nextcloud.

How does the Nextcloud app container find the database container?

The Nextcloud app container finds the database container through the MYSQL_HOST environment variable. The value is database, which matches the name of the MariaDB service in the Compose file.

Difference Between docker run and docker-compose up -d

docker run is used to create and start an individual container using command-line options. docker-compose up -d uses the Compose YAML configuration to create and start multiple related containers together in the background.
