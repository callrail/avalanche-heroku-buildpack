# AVALANCHE IS DEPRECATED

# Heroku Buildpack for avalanche

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for [avalanche](https://github.com/callrail/avalanche).

Runs the following:

1. `yarn run prod-build` - Asset compilation with webpack
2. `bundle exec rake i18n:js:export` - I18n translations export for frontend assets, via the `i18n-js` gem

## Usage

```bash
$ heroku config:set BUILDPACK_URL=https://github.com/callrail/avalanche-heroku-buildpack
```
