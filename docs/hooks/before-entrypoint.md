# before-entrypoint

```shell
/usr/bin/local/before-entrypoint.sh
```

## Example

```Dockerfile
FROM php:8

## Check internet connection on start up
RUN echo "ping -c5 8.8.8.8" > /usr/bin/local/before-entrypoint.sh
```

## Suppoerted by

- 
