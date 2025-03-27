# remote_mlflow
Containerized setup of remote mlflow

## MinIO setup

Make sure that the necessary data folder exist
```bash
$mkdir -p ${HOME}/minio/data
```
and then run it as

```bash
$docker compose up -d
```

then you can access it thorugh http://localhost:9001/

