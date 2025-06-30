# Hello World Node.js API

A simple Node.js API that returns "hello world" on GET requests.

## Quick Start

### Using Docker

1. Build the Docker image:
```bash
docker build -t hello-world-api .
```

2. Run the container:
```bash
docker run -p 3000:3000 hello-world-api
```

### Using Docker Compose

1. Start the service:
```bash
docker-compose up -d
```

2. Stop the service:
```bash
docker-compose down
```

## Testing

Once running, you can test the API by visiting:
- http://localhost:3000

Or using curl:
```bash
curl http://localhost:3000
```

You should see the response: `hello world`

## Files Structure

- `app.js` - Main application file with Express server
- `package.json` - Node.js dependencies and scripts
- `Dockerfile` - Docker container configuration
- `docker-compose.yml` - Docker Compose configuration for easy deployment