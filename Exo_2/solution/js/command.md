<!-- Build the image -->
docker build -t amaris/node:latest .

<!-- Run the container -->
docker run -it --name nodeAmaris -p 8000:8000 amaris/node:latest