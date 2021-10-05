## How to run with Docker

```bash
# Build Docker Image for reviews service
docker build -t image .

# Run reviews service on port 8081
docker run -d --name reviews -p 8081:8081 image 
```

* Test with path `/reviews/1` and `/health`

## License

MIT License