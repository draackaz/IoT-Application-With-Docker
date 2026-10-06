# IoT-software-docker
Essential applications needed to get your IoT network up and running with a Debian server. If you want to use it on another Linux distribution, follow the Docker installation guide.
- https://docs.docker.com/engine/install/

Once Docker is installed, add your server user to the docker group:
- sudo groupadd docker
- sudo usermod -aG docker $USER

The various configuration files are separated to make them easier to manage.

If you want to enhance monitoring, you can add Prometheus and Cadvisor:
- https://prometheus.io/
- https://github.com/google/cadvisor



