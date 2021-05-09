# Portainer with SSL Certificate in a Docker Swarm

Configure Traefik before applying the configuration.

Traefik configuration: https://github.com/heyValdemar/traefik-ssl-certificate-docker-swarm

Deploy Portainer in a Docker Swarm using the command:

`docker stack deploy -c portainer-traefik-ssl-certificate-docker-swarm.yml portainer`
