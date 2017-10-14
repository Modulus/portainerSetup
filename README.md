# Setup

You need to install docker and docker compose first

```
vagrant up
sudo su -
apt-get update
sudo apt-get install \
    apt-transport-https \
    ca-certificates \
    curl \
    software-properties-common
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
apt-get update
apt-get install docker-ce docker-compose
```
## Create the containers

```
cd /vagrant
docker-compose up -d
```

Open your browser at ![portainer](http://192.168.114.101/portainer)


