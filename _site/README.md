

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
JEKYLL_ENV=production bundle exec jekyll build
```

### Deploy

```
caprover deploy -a ayuda-chasqui
❯ clementina at https://captain.nube.clementina.coop
? git branch name to be deployed: main
? note that uncommitted and gitignored files (if any) will not be pushed to server! Are you sure you want to deploy? Yes
```
