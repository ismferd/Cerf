# cerf

[Serf](https://www.serf.io/) from Hashicorp in a Container image

## How can I use it?

By default, cerf use serf_0.8.1_linux_amd64.zip version.

If you want to run other version modify the [Dockerfile](cerf/Dockerfile) and choose your image from [serf](cerf/serf/)

In other case, just run:

```sh
docker run ismaelfm/serf serf
```
