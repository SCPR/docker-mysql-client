# docker-mysql-client
Dockerfile to build a super small mysql client.

## Usage:

Run the image to get into a shell:

```
    docker run -it scprdev/mysql-client:0.0.1 /bin/sh
```

In the container, run whatever mysql commands you need to connect:

```
    mysql -u SUPERSECRETUSER -h mysql.hostname.com -p
```