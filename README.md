# CECS326_Project0

Build Docker Image
- sudo docker build -t my-python-app .

Run Python Container
- sudo docker run my-python-app

Run the Nginx Web Server
- docker run -d -p 8080:80 -v $(pwd)/index.html:/usr/share/nginx/html/index.html nginx:latest

Open Browser to see Output
- http://localhost:8080

Check Running Containers
- sudo docker ps

Stop Container From Running
-  sudo docker stop (Enter CONTAINER ID)

Remove Container
- sudo docker rm (Enter CONTAINER ID)
