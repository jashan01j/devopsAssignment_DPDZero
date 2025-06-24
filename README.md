#Setup Instructions

-Clone the repository:

git clone <repository-url>
cd devops-assignment



-Run the system:

docker-compose up --build



-Access the services:

http://localhost:8080/service1/ping or /service1/hello for the Golang service
http://localhost:8080/service2/ping or /service2/hello for the Python service



View logs:

Nginx logs: docker exec -it <nginx-container-name> cat /var/log/nginx/access.log
Service logs: docker-compose logs service_1 or docker-compose logs service_2

Stop the system:

docker-compose down