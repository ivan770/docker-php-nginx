Laravel-ready Docker image
==============================================


Usage
-----
Build Docker image:

    docker build .

Start container:
    
    
    docker run -v /var/www/html/storage -t -i -p 80:80 <YOURIMAGE>
    
Note that this will create Docker volume with random ID for Laravel cache, logs, etc.
