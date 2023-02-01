

## Instalar para desarrollo

```
git clone git@github.com:Proyecto-Chasqui/ayuda.git
cd ayuda
gem install
```

### Correr servidor local

```
bundle exec jekyll serve
```

### Build

```
bundle exec jekyll build
```

### Build con docker

```
export JEKYLL_VERSION=3.8
docker run --rm \
  --volume="$PWD:/srv/jekyll:Z" \
  -it jekyll/builder:$JEKYLL_VERSION \
  jekyll build
```

### Deploy

```
caprover deploy -a ayuda-chasqui
❯ clementina at https://captain.nube.clementina.coop
? git branch name to be deployed: main
? note that uncommitted and gitignored files (if any) will not be pushed to server! Are you sure you want to deploy? Yes
```
