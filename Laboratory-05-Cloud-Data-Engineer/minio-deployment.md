# MinIO Deployment

## Docker Command

```bash
docker run -d -p 9000:9000 -p 9001:9001 --name minio-server \
-e "MINIO_ROOT_USER=cloudadmin" \
-e "MINIO_ROOT_PASSWORD=CloudNova2026!" \
minio/minio server /data --console-address ":9001"
```

## Web Console Port

The MinIO Web Console uses port **9001**.

## Bucket Name

The bucket created for the activity is:

**client-photos**

## Environment Variables

The `-e` flags set environment variables for the MinIO server.

* `MINIO_ROOT_USER=cloudadmin` sets the administrator username.
* `MINIO_ROOT_PASSWORD=CloudNova2026!` sets the administrator password.

These settings allow the administrator to log in to the MinIO Web Console.

