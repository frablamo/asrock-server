# Asrock-server Docker Config
based on configuration of @SergioRami https://raw.githubusercontent.com/SergioRami/raspberry-docker-config

## Requirements
Needs [docker](https://docs.docker.com/engine/install/) and [docker-compose](https://docs.docker.com/compose/install/).

## Usage

```
docker-compose -f app.yml up -d
```

## Images

The images used are:
- [emby](https://hub.docker.com/r/emby/embyserver) - Multimedia server
- [jackett](https://hub.docker.com/r/linuxserver/jackett) - Jackett works as a proxy server: it translates queries from apps (Sonarr, SickRage, CouchPotato, Mylar, etc) into tracker-site-specific http queries, parses the html response, then sends results back to the requesting software. This allows for getting recent uploads (like RSS) and performing searches. Jackett is a single repository of maintained indexer scraping & translation logic - removing the burden from other apps.
- [radarr](https://hub.docker.com/r/linuxserver/radarr) - Radarr - A fork of Sonarr to work with movies à la Couchpotato.
- [sonarr](https://hub.docker.com/r/linuxserver/sonarr) - Sonarr (formerly NZBdrone) is a PVR for usenet and bittorrent users. It can monitor multiple RSS feeds for new episodes of your favorite shows and will grab, sort and rename them. It can also be configured to automatically upgrade the quality of files already downloaded when a better quality format becomes available.
- [lidarr](https://hub.docker.com/r/linuxserver/lidarr) - Lidarr - A fork of Sonarr to work with series à la Couchpotato
- [qbitorrent](https://hub.docker.com/r/linuxserver/qbittorrent) - The Qbittorrent project aims to provide an open-source software alternative to µTorrent. qBittorrent is based on the Qt toolkit and libtorrent-rasterbar library.
- [syncthing](https://docs.linuxserver.io/images/docker-syncthing) - Syncthing project to have devices syncronized




