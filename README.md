# Docker Repo `collatzc/hexo-cli`

## Info

The Version in `LABEL` is the same as the tag of `node`. 

## Build & Push

```
# with tag
docker build -t collatzc/hexo-cli:<tag> .
docker push -t collatzc/hexo-cli:<tag>

# and latest
docker build -t collatzc/hexo-cli:latest .
docker push -t collatzc/hexo-cli:latest
```

## Log

* 7.2.1 Init