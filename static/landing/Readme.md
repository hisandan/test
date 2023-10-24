# Run Dockerfile
docker build -t static:latest .

docker run -p 8082:80  static:latest


