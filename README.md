# ACF - Wordpress

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

### Installation
Install plugin via composer. Add in file composer.json text below

Include package
```json
"require": {
        "kviron/advanced-custom-fields": "*"
    }
```
If need swiths paths installing, use command
```json
"extra": {
        "wordpress-install-dir": "public/wp",
        "wordpress-content-dir": "public/content",
        "installer-paths": {
            "wp-content/plugins/{$name}": [
                "type:wordpress-plugin"
            ],
            "wp-content/mu-plugins/{$name}": [
                "type:wordpress-muplugin"
            ],
            "wp-content/themes/{$name}": [
                "type:wordpress-theme"
            ]
        }
    }
```
And use command
```composer
composer update
```
