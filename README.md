# Heroku Buildpack: Python

This is a fork of the official [Heroku buildpack](https://devcenter.heroku.com/articles/buildpacks) for Python apps.

It only differs from the original (as of 2018-10-11) because it applies [PR #765](https://github.com/heroku/heroku-buildpack-python/pull/765), avoiding the cache clear and making it possible to install [Geospatial Libraries](https://github.com/CheesecakeLabs/heroku-geo-buildpack) without it being deleted.
