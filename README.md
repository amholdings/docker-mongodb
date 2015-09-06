# docker-mongodb
amholdings/docker-mongodb

Docker Conainer for MongoDB on CentOS7

# Build Container:
git clone https://github.com/amholdings/docker-mongodb.git

cd docker-mongodb

docker build --tag="docker-mongodb" .

# Run Container as daemon:

docker run -d --name "docker-mongodb" -p 27017:27017 amholdings/docker-mongodb
