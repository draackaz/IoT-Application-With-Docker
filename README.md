# IoT-software-docker
Basics application you need to begin your IoT network with a debian server if you want to use it on other linux distribution follow docker install guide

It's important to add user to docker group after docker install :
- sudo groupadd docker
- sudo usermod -aG docker $USER

If you want to enhanced monitoring you can add prometheus and cadvisor :
-https://prometheus.io/
-https://github.com/google/cadvisor
