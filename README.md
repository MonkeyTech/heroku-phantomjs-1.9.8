Heroku buildpack: PhantomJS
=======================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) of PhantomJS(http://phantomjs.org).

Usage
-----

Example usage:

```shell
$ heroku create --stack cedar --buildpack https://github.com/MonkeyTech/heroku-phantomjs-1.9.8

# or if your app is already created:
$ heroku buildpacks:add https://github.com/MonkeyTech/heroku-phantomjs-1.9.8

$ git push heroku master
```

based on: https://github.com/stomita/heroku-buildpack-phantomjs
