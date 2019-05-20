# Our First Dockerfile

```
FROM alpine:3.9

RUN mkdir -p /app
WORKDIR /app

COPY . /app/
```

## Dockerfile Essentials

### `FROM`

### `RUN`

### `COPY` / `ADD`

#### `COPY` vs `ADD`

* `ADD` unpacks `.tar` archives
* `ADD` allows source to be a URL

In general, prefer `COPY` over `ADD` (and use `curl` and/or `tar -x` for URLs and archives).
