## How to install php multi byte extension

Linux
```shell
sudo apt-get install php<version>-mbstring
```

Mac

```shell
brew install php<version>-mbstring
```

## Enable Multibytestring on extensions

```shell
;extensions=mbstring
;extensions=mbstring
```


## Enable using the CLI

NOTE:
phpenmod moduleName enables a module to php7 (restart apache after that sudo service apache2 restart)
phpdismod moduleName disables a module to php7 (restart apache after that sudo service apache2 restart)
php -m lists the loaded modules

If you have several php versions intalled you can also use this syntax:

phpenmod -v 5.6 <modulename>
phpenmod -v 7.1 <modulename>
