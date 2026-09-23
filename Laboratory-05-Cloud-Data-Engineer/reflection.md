# Mission Reflection

Object storage is better suited for storing millions of photos because it is designed for large amounts of unstructured data such as images, videos, and backups. Instead of treating the data like a traditional hard drive, object storage keeps files as objects that can be accessed and managed easily. This makes it suitable for a photo-sharing application that may need to store many user-uploaded images.

Docker made it easier to deploy the MinIO storage server because I did not need to manually install and configure all the required components. By using a Docker command, MinIO could be downloaded and started in a container with the required ports and environment variables. This made the deployment process faster and more organized.

A bucket is a storage container used to organize and store objects in object storage. In this activity, the bucket I created was named `client-photos`, and I used it to store the uploaded sample file.

Large enterprise companies can help prevent data loss by keeping copies or backups of their data and using multiple storage systems or physical servers. If one physical server crashes, another copy can help keep the data available. This is important because cloud storage needs to be reliable and accessible.

My confidence in navigating the Linux command line is growing because I was able to use commands to deploy and check the MinIO container. I also learned how Docker commands can be used to run cloud services. This activity helped me understand how object storage works and gave me more experience with Linux, Docker, MinIO, and cloud storage.
