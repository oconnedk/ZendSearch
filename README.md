# ZendSearch component

## PHP 8 Note

In order to get this to work with PHP 8, I am using [laminas/laminas-zendframework-bridge](https://github.com/laminas/laminas-zendframework-bridge) as a bridge to the abandoned [zendframework/zend-stdlib](https://github.com/zendframework/zend-stdlib) within the [composer.json](composer.json) config.

This might not work with all features as it seems there are [some issues even on PHP 7](https://github.com/zendframework/ZendSearch/issues?q=is%3Aissue+is%3Aclosed).


> ## UNMAINTAINED
>
> This package is no longer maintained.

You can install using:

```
curl -s https://getcomposer.org/installer | php
php composer.phar install
```

At that point, follow the instructions in the documentation folder for actual
usage of the component. (Documentation is forthcoming.)
