## What is Two-Tier Architecture?

A two-tier architecture is a system where the application and database are separated into two different parts or tiers. In this laboratory, the Nextcloud application is one tier, while the MariaDB database is the second tier.

# The Web/Application Tier

The web/application tier is responsible for providing the user interface and handling requests from users. In this project, Nextcloud is the application that users access through a web browser.

# The Database Tier

The database tier is responsible for storing important information such as user accounts, passwords, and file metadata. In this project, MariaDB is used as the database.

# Why Separate Them?

It is better to separate the web application and database because each part has its own job. Using separate containers makes the system easier to manage, update, troubleshoot, and scale. If there is a problem with one container, it can be handled without directly affecting the other part.
