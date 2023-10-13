# Backstage

This is your newly scaffolded Backstage App, Good Luck!

To start the app, run:

set github [cred](https://github.com/settings/applications/new) in docker-compose.yml

after that you can run backstage service:

```sh
docker-compose up -d
```

hello-world app catalog added in app-config.yml

```yml
catalog:
  locations:
    - type: url
      target: https://github.com/vamirreza/hello-world/blob/main/catalog-info.yaml
```