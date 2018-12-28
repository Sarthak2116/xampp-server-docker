# xampp-server-docker
This project has a docker file which can be used to create a container having XAMPP Server with PHPMyAdmin and MySQL

TO use the container on your docker, use:

docker run --name XamppTestServer -p 41061:22 -p 41062:80 -d -v $(pwd):/www sarthak321321/xampp-server

To access the *.php files visit
localhost:41062/www
