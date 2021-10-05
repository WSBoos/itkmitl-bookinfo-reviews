## How to run with Docker

```bash
# Build Docker Image for reviews service
docker build -t image_reviews .

# Run reviews service on port 8082
docker run -d --name reviews -p 8082:8082 image_reviews
```

* Test with path `/reviews/1` and `/health`

## How to run with Docker-Compose

```bash
docker-compose up -d
```

## License

MIT License