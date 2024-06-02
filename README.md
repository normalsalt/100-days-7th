# 100 Days Challenge 7th Period Archive

```
docker compose up -d
open http://localhost:1313/100-days-7th/
```

```
docker compose run --rm hugo hugo new content posts/100-days-7th.md
```

## installation

https://gohugo.io/installation/linux/

```
docker run --rm -v .:/content -w /content -it alpine:latest sh
apk add --no-cache --repository=https://dl-cdn.alpinelinux.org/alpine/edge/community hugo
hugo new site my-site
```

```
git submodule add -b main https://github.com/1bl4z3r/hermit-V2 my-site/themes/hermit-v2
```

## deployment

https://gohugo.io/hosting-and-deployment/hosting-on-github/
