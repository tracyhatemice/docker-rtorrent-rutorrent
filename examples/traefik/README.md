## Usage

```shell
mkdir config data passwd
chown ${PUID}:${PGID} config data passwd
touch acme.json
chmod 600 acme.json
docker compose up -d
docker compose logs -f
```
