# hotfix-module-7743
OXID eShop hotfix module for https://bugs.oxid-esales.com/view.php?id=7743

Stabilized: Exception during render in Smarty oxcontent plugin is caught and logged.

# Compatibility

### Versions
* versions `1.0.x` - compatible with OXID eShop compilation 6.2 to 6.5
* versions `2.0.x` - compatible with OXID eShop compilation 6.2 to 6.5 with extended hotfix
* versions `3.0.x` - compatible with OXID eShop compilation 7.0 and SMARTY template engine with extended hotfix

### Branches
* `b-6.5.x` is compatible with OXID eShop b-6.2.x up to b-6.5.x
* `b-7.0.x` is compatible with OXID eShop b-7.0.x

### Module installation via composer

In order to install the module via composer run one of the following commands in commandline in your shop base directory
(where the shop's composer.json file resides).

```shell
composer require oxid-esales/hotfix-module-7743:^3.0.0
```
to install the latest released version compatible with OXID eShop v7.0.x

### Module activation

```shell
    vendor/bin/oe-console oe:m:ac oe_hotfix_7743
```
