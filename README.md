docker build -f Dockerfile.dev -t react .


docker run --publish 3000:3000 react
