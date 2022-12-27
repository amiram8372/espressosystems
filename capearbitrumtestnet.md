## Required features that the system is recommended to have
- I advise you to choose a system with 4 processors and 8 GB of RAM so that you can quickly handle the processes.
- Ubuntu 20.04

## Install the desktop version of Ubuntu
```
sudo apt update
sudo apt-get dist-upgrade
sudo apt-get install ubuntu-desktop
wget https://download.nomachine.com/download/7.9/Linux/nomachine_7.9.2_1_amd64.deb
sudo dpkg -i nomachine_7.9.2_1_amd64.deb
sudo adduser kullanici
usermod -aG sudo kullanici
reboot
```

## Testnet Setup
```
sudo curl -fsSL https://get.docker.com -o get-docker.sh && sh get-docker.sh
sudo apt install docker-compose
sudo curl https://www.espressosys.com/cape/docker-compose.yaml --output docker-compose.yaml
sudo docker-compose pull
sudo docker-compose up
```

## Testnet İşlemleri
- After performing the operations, we perform the steps in the video by typing ``localhost`` in the browser.
     - 

