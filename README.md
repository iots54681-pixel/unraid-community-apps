# Unraid Community Apps Templates

Community-maintained Unraid application templates by **iots54681-pixel**.

## Hades

This repository provides an Unraid Community Applications template for Hades.

Hades is a self-hosted media management server and companion backend for Icarus. It centralizes supported media-service connections and provides a unified library for Icarus clients.

### Supported integrations

Hades supports media services including:

- Sonarr
- Radarr
- Seerr
- Additional integrations supported by Hades

### Docker image

This template deploys the official Hades Docker image:

`docker.io/mypantheon/hades-server:latest`

### Persistent storage

Hades stores its persistent configuration and databases at:

`/config`

The Unraid template maps this by default to:

`/mnt/user/appdata/hades`

### Web interface

Hades uses TCP port `8124` by default.

## Support

For issues specifically related to this **Unraid template**, please use this repository's GitHub Issues page.

For issues with Hades or Icarus themselves, please use the official Hades/Icarus support resources.

## Disclaimer

This is a community-maintained Unraid deployment template.

Hades and Icarus are developed and distributed by their respective developers. This repository is not the official source repository for Hades or Icarus.
