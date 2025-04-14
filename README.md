# Hello Node Docker App

This is a simple Node.js app that runs inside a Docker container and prints "Hello, Docker World!" in the browser.

## How to Run

1. Clone the repository:

2. Build the Docker image:
  docker build -t hello-node .
  
3. Run the container:
docker run -p 3000:3000 hello-node

4. Open your browser and go to:
   http://localhost:3000

## Docker Hub

You can pull the image directly from Docker Hub:
  docker pull nimi707/hello-node
  
---

That's it!

