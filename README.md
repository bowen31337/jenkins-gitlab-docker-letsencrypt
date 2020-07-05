# Gitlab + Jenkins + Docker Compose running with auto generate/renew Let's Encrypt Certificate


## PREREQUISITES

In order to use this compose file (docker-compose.yml) you must have:

- docker https://docs.docker.com/engine/installation/
- docker-compose https://docs.docker.com/compose/install/
- docker-compose-letsencrypt-nginx-proxy-companion https://github.com/evertramos/docker-compose-letsencrypt-nginx-proxy-companion

## HOW TO USE 

1. Close this repository

```bash
$ git clone https://github.com/bowen31337/jenkins-gitlab-docker-letsencrypt.git
```

2. Make a copy of the `.env.example` and rename it to `.env`:

```bash
cp .env.example .env
```

Update this file with your preferences.


4. Start the container.

During the build time, the environment variables are injected into the image.

```bash
$ docker-compose up -d
```

