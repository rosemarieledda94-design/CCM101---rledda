# Mission 4 Reflection

Docker containers are much faster to set up compared to installing an operating system on a Virtual Machine. A Virtual Machine needs a complete guest operating system, which can take several minutes to boot and uses more RAM. A Docker container is lightweight and can start in seconds because it shares the host operating system. This makes containers useful when applications need to be deployed quickly.

Port mapping such as "-p 8080:80" is necessary because the Nginx web server is running inside the container on port 80. The mapping connects port 8080 on the host to port 80 inside the container. This allows users to access the web server through "localhost:8080".

When the "docker rm" command is used, the container is removed completely. Any data stored only inside the container that is not saved using persistent storage is also lost. Therefore, important data should be stored outside the container when it needs to remain available.

Containerization can change how software developers and IT operations teams work together. Developers can package an application and its dependencies into a container, while IT operations teams can deploy the same container in different environments. This supports a more consistent workflow between development and operations and is useful for DevOps practices.

My GitHub portfolio is evolving as I add more laboratory activities and technical documentation. This activity adds Docker, containerization, and cloud-native skills to my portfolio. The screenshots and Markdown files also provide evidence of the commands and procedures I completed. Overall, this laboratory helped me understand how containers can make application deployment faster, lightweight, and easier to manage.





