# Half-Life Deathmatch: Source Dedicated Server in Docker

## Linux

[![](https://images.microbadger.com/badges/version/lacledeslan/gamesvr-hldms.svg)](https://microbadger.com/images/lacledeslan/gamesvr-hldms "Get your own version badge on microbadger.com")
[![](https://images.microbadger.com/badges/image/lacledeslan/gamesvr-hldms.svg)](https://microbadger.com/images/lacledeslan/gamesvr-hldms "Get your own image badge on microbadger.com")

### Download

```shell
docker pull lacledeslan/gamesvr-hldms
```

### Run Self Tests

```shell
docker run -it --rm lacledeslan/gamesvr-hldms ./ll-tests/gamesvr-hldms.sh
```

### Run Interactive Server

```shell
docker run -it --rm --net=host lacledeslan/gamesvr-hldms ./srcds_run -game hl1mp +map crossfire -maxplayers 8 +sv_lan 1
```
