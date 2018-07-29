# bpanel-docker

running bpanel and bcoin with traefik and docker-compose

## how to

```
git clone --recursive https://github.com/joemphilips/bpanel-docker
```
And then, put ssl certificate and key into `./cert`

```
docker network create traefik_proxy
docker network create apps
docker-compose up
```

