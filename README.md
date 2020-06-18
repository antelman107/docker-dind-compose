Dockerfile:

```
FROM docker:dind
RUN apk add --update --no-cache docker-compose && rm -rf /var/cache/apk/*
MAINTAINER ant.elmanov@gmail.com
```