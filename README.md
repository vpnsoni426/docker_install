install doker ---> sudo apt install docker.io

change permission in azure ubuntu --> useradd -G docker azureuser

install docker compose ansible machine --> apt install docker docker-compose

install python on ubuntu machine ==>apt install python3 python3-pip
===>apt-get install pip

install ansible also --> sudo apt-add-repository ppa:ansible/ansible
=----> sudo apt update
---> sudo apt install ansible


check playbook correct or not --> ansible-playbook app-play.yml --check

ansible -m ping ansi-host


run playbook --> ansible-playbook app-igct.yml

docker build image ---> docker build -t java-webapp-kuber .
docker run --> docker run -d -p 8080:8080 java-webapp-kuber:latest
