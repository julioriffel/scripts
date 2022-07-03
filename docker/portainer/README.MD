## Instalar/Atualizar Portainer

```
docker container stop portainer 
docker container rm portainer
docker volume rm portainer_data
docker pull cr.portainer.io/portainer/portainer-ce:latest
docker volume create portainer_data
docker run -d -p 9001:8000 -p 9000:9000 --name portainer --restart=always -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/data cr.portainer.io/portainer/portainer-ce:latest
```
