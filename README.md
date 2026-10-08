# Git and Docker Starter Application

This repository contains a small Python web application used to practice Git, GitHub, and Docker workflows.

## Application

The application listens on port 8000 and returns a text response when accessed over HTTP.

## Verification

The running application should be verified using an HTTP request to port 8000.


## Usage

Build the image:

```bash
docker build -t git-docker-app:test .
```

Run the application and map host port 8080 to application port 8000:

```bash
docker run --rm -p 8080:8000 git-docker-app:test
```

Then open `http://localhost:8080`, or run `curl http://localhost:8080`.

