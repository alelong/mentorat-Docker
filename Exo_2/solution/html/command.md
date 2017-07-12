<!-- Build the image -->
docker build -t amaris/nginx:latest .

<!-- Run the container -->
docker run --name nginxAmaris -p 80:80 -d amaris/nginx:latest