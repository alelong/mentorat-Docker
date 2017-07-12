<!-- Build the image -->
docker build -t amaris/mongo:latest .

<!-- Run the container -->
docker run --name mongoAmaris -p 27017:27017 -d amaris/mongo:latest