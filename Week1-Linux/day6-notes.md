# Day 6 - NGINX Web Server and Service Management

Commands practiced
sudo apt update
sudo apt install nginx
sudo systemctl start nginx
sudo systemctl status nginx
sudo systemctl restart nginx
ss -tulnp
curl localhost

Learnings
apt is used to install packages on Ubuntu
nginx is a web server that serves HTTP traffic
systemctl manages services (start, stop, restart)
ss -tulnp shows open ports and listening services
nginx listens on port 80 by default
curl localhost sends an HTTP request to the local server
Seeing the "Welcome to nginx" page confirms the service is running
