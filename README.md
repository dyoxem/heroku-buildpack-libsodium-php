# Heroku buildpack: libsodium-php

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for the `libsodium-php` extension, based on [heroku-buildpack-libsodium](https://github.com/envato/heroku-buildpack-libsodium).

Needs to be run as part of [heroku-buildpack-multi](https://github.com/heroku/heroku-buildpack-multi), **after** [heroku-buildpack-php](https://github.com/heroku/heroku-buildpack-php).

Installs libsodium 1.0.3 and libsodium 1.0.0 by default, this can be changed by adding a file named .sodium_params to the root of your project and adding following lines to it:

LIBSODIUM_VERSION=x.x.x

LIBSODIUM_PHP_VERSION=x.x.x

Project is still in development, use with caution.
