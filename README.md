# ePages 6 Devtools
Gulp taskrunner for ePages 6 development.

_Install it with the [ePages 6 Yeoman Generator](https://github.com/ePages-rnd/generator-epages6)_

## Available gulp tasks

``default``: Triggers ``watch``

``build``: Runs ``make build_ui``

``watch``: Runs file watchers for ``scripts``, ``styles``, ``perl`` and ``html``, based on your settings

``scripts``: Copies modified and new JavaScripts to the webroot via scp

``styles``: Copies modified and new less and css files to the webroot via scp

``html``: Runs remote tle linting on the vm

``perl``: Runs remote perl linting on the vm
