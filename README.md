# zigbee2mqtt deployment

This repository represents a deployment of [zigbee2mqtt](https://www.zigbee2mqtt.io/) & mqtt on a Orange Pi Zero LTS powered by a POE splitter 

![image](https://user-images.githubusercontent.com/319498/109385440-bdafe100-78eb-11eb-8f8e-38ec95ad9293.png)


# install

```bash
apt update
apt upgrade -y

hostnamectl set-hostname zigbee-orange-pi

apt install git zip unzip curl vim -y

curl -fsSL https://get.docker.com -o get-docker.sh | sudo sh ./get-docker.sh

apt install docker-compose -y

apt install unattended-upgrades -y

dpkg-reconfigure --priority=low unattended-upgrades
```
