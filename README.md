This is a Dockerfile to have a recently updated version of telegram-cli working in 2020 without segfaulting. Hopefully...

The corresponding Lua script is here: https://github.com/kenorb-contrib/tg

## Crear Docker

```
docker create  --name telegram-cli  ugeek/telegram-cli:amd64
```

## Indicar telegram-cli
```
docker start telegram-cli
```

## Iniciar telegram-cli
```
docker exec -it telegram-cli telegram-cli
```

