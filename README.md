# docker-compose-gravitee-am-singlegw

## Description

Docker Compose environment with:

- Traefik Ingress
- Gravitee Access Management 3.x

## DNS entries

Add the next entries to the /etc/hosts file (or DNS registry)

```
127.0.0.1   am-gw.demo.chakray.internal am-api.demo.chakray.internal am-webui.demo.chakray.internal
```

## Startup

```
docker-compose up -d
```

Login Access Management Console: http://am-webui.demo.chakray.internal:90/

User: admin
Password: adminadmin


