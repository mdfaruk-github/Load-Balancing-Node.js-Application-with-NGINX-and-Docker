sudo docker build -t load-balance-nginx .

sudo docker run -p 8080:80 -d load-balance-nginx
