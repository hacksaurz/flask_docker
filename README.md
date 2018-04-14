# build image
docker build -t flask_docker:1.0 .

# spin up container
docker run -d -p 5000:5000 flask_docker:1.0

# ...

# profit
http://127.0.0.1:5000/
