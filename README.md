wercker-openresty-build
=======================

This is an automatic way to use [Wercker](http://wercker.com/) to:

1. Build an Ubuntu package of [Openresty](http://openresty.org/) - with [fpm-cookery](https://github.com/bernd/fpm-cookery) and the recipe located [here](https://github.com/darron/fpm-recipes/tree/master/openresty).
2. Upload it to my [apt repo](https://packagecloud.io/darron/openresty) at [packagecloud](https://packagecloud.io/).

It occurs anytime you update this repo and trigger a build.
