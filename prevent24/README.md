# Testing in Docker

```shell
docker run --rm --volume="$(pwd):/srv/jekyll" -it -p4000:4000 jekyll/jekyll jekyll serve
```
