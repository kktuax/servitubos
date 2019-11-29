# maxtuni.es 

## Run locally with docker

```sh
export JEKYLL_VERSION=3.8
docker run --rm --network=host -v "$PWD/.bundlecache:/usr/local/bundle" -v "$PWD:/srv/jell" jekyll/jekyll:$JEKYLL_VERSION  jekyll serve
```
