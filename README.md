# Centrifugo Base

Instant messaging server starter using Centrifugo and Traefik.

## Traefik Documentation

This template uses Traefik (<https://traefik.io/>), an edge router and reverse proxy written in Go.

To start, make sure to configure your Traefik instance or remove some Traefik-related configs in your docker compose file.

When using Traefik, you can easily deploy using <https://github.com/Nuxify/traefik-setup>.

## Centrifugo Documentation

Refer to official Centrifugo site: <https://centrifugal.dev/docs/getting-started/quickstart>.

1. Clone <https://github.com/Nuxify/node-centrifugo>

2. Create .env file from .env.example

```bash
cp .env.example .env
```

3. Create config file then edit the configs

```sh
# generate config file
cp config.example.json config.json
```

4. Up the centrtifugo container with

```bash
make up
```

To check all server configurations, visit <https://centrifugal.dev/docs/server/configuration>.

Made with ❤️ at [Nuxify](https://nuxify.tech)
