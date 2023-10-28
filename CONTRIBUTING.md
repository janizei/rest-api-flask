# CONTRIBUTING

## How to run the Dockerfile locally

```
docker run -dp 5000:5000 -w /app -v "$(pwd):/app" IMAGE_NAME sh -c "flask run --host 0.0.0.0"

Remember to provide .env file with the DATABASE_URL. You can see the example .env.example on the root directory of the project.
```