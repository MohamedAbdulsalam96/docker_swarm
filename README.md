# <p align="center">Docker Swarm</p>
### <p align="center">A deployment method and collection of basic docker swarm stacks.</p>

## Prerequisites:
* **_Tested on_ Ubuntu Server 20.04 LTS Local or [VPS](https://ca.ovh.com/au/order/vps/) Server**
* **SSH Access**
* **Firewall configured to allow 80, 443, 22**
* **Public, static IP**
* **[Domain](https://domains.google.com/) pointing to servers public IP address**

## Notes:
* **Designed to be executed on a fresh platform**
* **All updates are handled**

## Deployment:
* **This will bring up Traefik and Portainer on a primary Docker Swarm node**
```
sudo groupadd docker
sudo usermod -aG docker $USER
newgrp docker
curl -fsSL https://raw.githubusercontent.com/suodrazah/docker_swarm/main/deploy.sh -o deploy.sh && sh deploy.sh
```

## Extension:
* **Follow instructions in each stack.yml file. I'll add it all here as I upload them**

## Demo:
* **Username: `demo`**
* **Password: `demo`**

traefik.demo.suodrazah.com.au
portainer.demo.suodrazah.com.au
