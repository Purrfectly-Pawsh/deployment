# Deployment

In order to have an easier time presenting the final product and not having to open too many different terminal tabs we have decided to utilize a single `docker-compose.yaml` Deployment file. 

## Usage

1. This repository should be in the same directory as the other project folders because the checkout and order service are not pushed to DockerHub and need to be built locally.

```
|
| - product-service
| - basket-service
| .
| .
| .
| - deployment
```

2. Change into the directory of this repository 

```bash 
cd deployment
```

3. Start the deployment
```bash
docker compose up -d
```

4. Open your browser of choice and navigate to `http://localhost:5173` where the frontend service is running. 
