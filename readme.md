### OXID 6 example module
A simple and basic OXID 6 module. 

## Install via composer

`composer require linslin/oxid6-example-module:dev-master`


## Add to root composer.json
For developing with a local copy which is not registered

    "repositories": [
        {
            "type": "path",
            "url": "./source/modules/linslin/oxid6-example-module"
        }
    ],
    "require": {
        "linslin/oxid6-example-module": "dev-master"
    },
