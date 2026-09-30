Mission Reflection

Writing a docker-compose.yml file makes a cloud engineer's job easier because the configuration for multiple containers can be written in one file. Instead of manually typing many commands to create and connect each container, Docker Compose can use the configuration to deploy the services together. This also makes the deployment easier to repeat and manage.

An indentation error in a YAML file can cause problems because YAML depends on proper spacing and indentation. For example, using a Tab instead of spaces or placing a line at the wrong level can cause Docker Compose to reject the file or misunderstand the configuration. This is why the YAML file must be carefully formatted.

We used environment variables such as MYSQL_PASSWORD to provide the configuration information needed by the containers. These variables allow the Nextcloud application to connect to the MariaDB database using the required database password, database name, username, and host.

Deploying Nextcloud in just a few minutes showed me how useful cloud technologies and containerization can be. Instead of manually installing every part of the system, Docker Compose allowed the Nextcloud application and MariaDB database to be deployed as connected containers.

Since Mission 1, my understanding of Cloud Computing has evolved. I now understand that cloud computing is not only about storing files or using online services. It also involves infrastructure, containers, automation, deployment, and managing services efficiently. This mission helped me understand how Infrastructure as Code can make cloud deployment more organized, repeatable, and easier to manage.
