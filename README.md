### Altix Developers Site

___

## Dokku Buildpacks

1. https://github.com/heroku/heroku-buildpack-ruby.git
2. https://github.com/heroku/heroku-buildpack-static.git

```
# Config buildpacks in dokku server
dokku buildpacks:add dev.altix.co https://github.com/heroku/heroku-buildpack-ruby.git
dokku buildpacks:add dev.altix.co https://github.com/heroku/heroku-buildpack-static.git

```
