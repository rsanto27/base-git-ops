To build image

docker build -t my-go-server .

To run container

docker run -p 8080:8080 my-go-server
docker run --rm -p 8080:8080 rsanto27/my-go-server:latest