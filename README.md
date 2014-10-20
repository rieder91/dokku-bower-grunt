dokku-bower-grunt
=================

This plugin will do the following:
 * Run `npm install` in the app directory (which will also install devDependencies)
 * Install `grunt`, `grunt-cli` and `bower` globally
 * Do a `bower install --allow-root`
 * Execute `grunt`

## Install

On your dokku server run:
```sh
cd /var/lib/dokku/plugins
git clone https://github.com/rieder91/dokku-bower-grunt.git dokku-bower-grunt
```

No `dokku plugin-install` necessary!