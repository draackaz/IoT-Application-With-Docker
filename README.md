# IoT-software-docker
Basics application you need to begin your IoT network with a debian server if you want to use it on other linux distribution follow docker install guide

After docker install add your server user to docker group :
- sudo groupadd docker
- sudo usermod -aG docker $USER

The different config file are separated to maintain them more easly

If you want to enhanced monitoring you can add prometheus and cadvisor :
- https://prometheus.io/
- https://github.com/google/cadvisor
