# Neos CMS plugin for more configurable login wallpapers

This package modifies the Neos CMS login slightly to allow using absolute http urls.
After installation it will show a random image from [unsplash](https://source.unsplash.com) as default.

This feature is meant to be integrated in one of the next Neos releases,
but this plugin provides the same for older installations for Neos 5.3+.
Neos 4.3 is not supported as the login is not yet Fusion based.

## Installation

Install the package via composer:

```bash
composer require shel/neos-login-wallpapers
```

## Configuration

```yaml
Neos:
    Neos:
        userInterface:
            backendLoginForm:
                backgroundImage: 'https://source.unsplash.com/random'
```
