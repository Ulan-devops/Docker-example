# Docker-example


NOTE: First install Docker as instructed in CLASS 1 Dockeras below

yum repolist
yum install -y wget
wget -qO- https://get.docker.com/ |sh
to know kernel version: uname -r 
yum update kernel -y
docker --version
systemctl enable docker
systemctl start docker
docker images
docker ps 
