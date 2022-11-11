# watchtower

## Usage

``` bash
# https://containrrr.dev/watchtower/arguments/
docker run --detach=true \
    --name=watchtower \
    --restart=always \
    --volume=/var/run/docker.sock:/var/run/docker.sock \
    containrrr/watchtower \
    --cleanup
```
