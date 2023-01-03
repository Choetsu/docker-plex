# docker-plex


## Pour lancer le projet


1. Clonez le repo
2. Lancez les dockers : ```docker compose -f docker-compose-overseer.yml up -d && docker compose up -d```
3. Renommez le fichier .env.example en .env et changez le contenu

Vous pouvez maintenant accéder aux différents services et les paramétrer via les urls suivantes :
* plex : <your-ip>:32400/web
* overseerr : <your-ip>:5055
* radarr : <your-ip>:7878
* sonarr : <your-ip>:8989
* bazarr : http://<host-ip>:6767
* prowlarr : <your-ip>:9696
