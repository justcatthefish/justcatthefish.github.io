# website
## Local test

### With docker
`docker compose up`

### Without docker

Install [hugo](https://gohugo.io/), then start the server
```bash
hugo server

# this one ensures full rebuilds on changes
hugo server --disableFastRender
```

## Building for deployment
Build & minify, upload contents of `public/` onto the webserver
```bash
hugo --minify
```
