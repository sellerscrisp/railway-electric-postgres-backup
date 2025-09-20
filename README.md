# Railway Electric-SQL with S3-compatible Backup

## Environment Variables

```dotenv
DATABASE_URL = ${{Postgres.DATABASE_URL}}

STORAGE_PROVIDER = S3

S3_BUCKET = e.g. electric-backups

AWS_ACCESS_KEY_ID = ${{MinIO.MINIO_ROOT_USER}}

AWS_SECRET_ACCESS_KEY = ${{MinIO.MINIO_ROOT_PASSWORD}}

S3_ENDPOINT = http://minio:9000 (or your MinIO service’s internal URL)

S3_PATH_STYLE = true (MinIO prefers path-style)
```