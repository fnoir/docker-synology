# Docker sur Synology

## VPN

### Clients

Copier le fichier _fichier.ovpn_ dans _~/appdata/rtorrent/config/openvpn/_

### Tun Adapter

Sur Synology, ajouter une tâche planifiée :
* Nom : Start TUN Adapter
* Utilisateur : root
* Évènement : Démarrage
* Commande : chemin/vers/tun.sh

## Plex Claim

Se rendre sur [https://www.plex.tv/claim](https://www.plex.tv/claim) et copier le code (valable 5 minutes)

## UserID et GroupID

Se connecter en SSH sur le NAS et taper :

```bash
id nom_de_l_utilisateur
```

# Images

[Docker Socket Proxy](https://hub.docker.com/r/tecnativa/docker-socket-proxy)
[Traefik](https://hub.docker.com/_/traefik)
[Deemix](https://gitlab.com/Bockiii/deemix-docker)
[Jackett](https://hub.docker.com/r/linuxserver/jackett)
[Plex](https://hub.docker.com/r/plexinc/pms-docker)
[Radarr](https://hub.docker.com/r/linuxserver/radarr)
[rTorrent](https://hub.docker.com/r/binhex/arch-rtorrentvpn)
[Sonarr](https://hub.docker.com/r/linuxserver/sonarr)
[Tautulli](https://hub.docker.com/r/linuxserver/tautulli)
[Watchtower](https://hub.docker.com/r/containrrr/watchtower)
