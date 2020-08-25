![docker-publish-to-dh](https://github.com/swaglive/docker-s6-overlay/workflows/docker-publish-to-dh/badge.svg)

# Usage

```Dockerfile
FROM s6-overlay as s6-overlay

FROM alpine:3.7

COPY --from s6-overlay / /
```
