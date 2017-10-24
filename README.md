# Create the containers

```
cd portainerSetup
docker-compose up -d
docker-comopse logs 
```

Point your browser to http://192.168.114.101/portainer



## Vagrant setup

To test this in vagrant, you need to run the following You need to install docker and docker compose first

```
vagrant up
sudo su -
cd /vagrant
sh install_docker.sh
```

