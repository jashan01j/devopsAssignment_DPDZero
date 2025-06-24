#Setup Instructions

-#Clone the repository:
git clone <repository-url>
cd devopsAssignment_DPDZero



-#Run the system:
docker-compose up --build



-#Access the services:
http://localhost:8080/service1/ping or /service1/hello for the Golang service
http://localhost:8080/service2/ping or /service2/hello for the Python service



-#Stop the system:
docker-compose down
