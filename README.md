# Getting Started

1. sudo docker pull redis/redis-stack-server:latest

2. sudo docker run -d --name redis-stack-server -p 6379:6379 redis/redis-stack-server:latest

1. Execute via spring the application `CoreBackendApplication`

2. Call rest api http://localhost:8081/api

3. Test will be executed with mvn test
