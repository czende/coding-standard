<h1 align="center">
    Czende Coding Standard
</h1>

:1st_place_medal: Coding standard configuration.

Installation & usage
--------------------

1. Install this package:

    ```bash
    $ composer require --dev czende/coding-standard
    ```
    
2. Import a configuration file in `easy-coding-standard.yml` in the root of your project:

    ```yml
    imports:
        - { resource: vendor/czende/coding-standard/easy-coding-standard.yml }
    ```
3. Run in CLI (remember to have proper composer bin directory config - `"bin-dir": "bin"`)

```bash
# dry
php bin/ecs check src

# fix
php bin/ecs check src --fix
```