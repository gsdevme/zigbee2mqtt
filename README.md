# zigbee2mqtt deployment

This repository represents a deployment of [zigbee2mqtt](https://www.zigbee2mqtt.io/) & mqtt on a Raspberry Pi v3 B

# install

```bash
sudo apt update
sudo apt upgrade -y

sudo hostnamectl set-hostname zigbee2mqtt.local

# Reduce the GPU memory to 16mb
sudo raspi-config nonint do_memory_split 16

sudo apt install git zip unzip curl vim -y

curl -fsSL https://get.docker.com -o get-docker.sh | sudo sh ./get-docker.sh

sudo apt install docker-compose -y

sudo apt install unattended-upgrades -y

sudo dpkg-reconfigure --priority=low unattended-upgrades

```
