## About

A simple app that lists all environment variables, used to demonstrate [config vars](https://devcenter.heroku.com/articles/config-vars).

## Deploy

Deploy the app to Heroku by pushing the button:

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Add a config var

Either used Dashboard, or the CLI:

```
heroku config:set FOO=123
```

Refresh the app to see `FOO` is now available as an environment variable

