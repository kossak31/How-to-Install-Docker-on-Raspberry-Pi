# How-to-Install-Docker-on-Raspberry-Pi
como instalar o docker num raspberry pi


## Step 1: Update and Upgrade
```
sudo apt-get update && sudo apt-get upgrade
```

## Download the Convenience Script and Install Docker on Raspberry Pi
```
curl -fsSL https://get.docker.com -o get-docker.sh
sudo sh get-docker.sh
```


## Add a Non-Root User to the Docker Group
```
sudo usermod -aG docker pi
```

## Check Docker Version and Info
```
docker version
docker info
```

## How to Uninstall Docker on Your Raspberry Pi?
```
sudo rm -rf /var/lib/docker
sudo apt-get purge docker-ce-cli
```
