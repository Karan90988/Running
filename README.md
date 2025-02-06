# Running
Running a static website using apache (httpd):
docker run -d -p 8080:80 -v $(pwd)/web:/usr/local/apache2/htdocs:ro httpd:2.4

Running a static website using nginx server :
docker run -d -p 8081:80 -v $(pwd)/web:/usr/share/nginx/html:ro nginx:latest

