##changing usermode
```bash
sudo usermod -aG docker $USER && newgrp docker
```
##starting minikube
```bash
minikube start --driver=docker
```
