# newman-reporter-html-template-email
HTML template for [newman-reporter-html](https://github.com/postmanlabs/newman-reporter-html).
This needs to be used in conjunction with Newman so that it can recognize HTML reporting options.

## Usage
In order to enable this template, specify `template-email.hbs` in Newman's `--reporter-html-template` option.

```console
$ newman run https://www.getpostman.com/collections/631643-f695cab7-6878-eb55-7943-ad88e1ccfd65-JsLv -r html --reporter-html-template template-email.hbs
```
