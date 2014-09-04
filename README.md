# TEDxLausanne website

## Compilation Theme

To build and watch your files, make sure you are in the root of the project. Then run the following commands.


```shell
$ npm install
```

# Rebuild from ../tedxlausanne-styleguide
```shell
$ gulp build
```

# Deploy
We use [Capdrupal](https://github.com/antistatique/capdrupal) for D7 (v0.x) to deploy.

## First time

    $ gem install bundle
    $ bundle install

## Then

    $ bundle exec cap dev deploy