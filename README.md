# Alliance bank

Alliance bank payment gateway integration.

## Installation

### Manually

* Create a free Alliance bank account https://portal.albpay.io/mportal/ 
* Copy the module folder into the ```<thelia_root>/local/modules/``` directory and make sure that the name of the folder is ```Fondy``` or create zip archive which contains folder ```Fondy/{all files from this repository}``` and install from administration side.
* Activate Alliance bank in your Thelia administration panel.

### Composer

Add it in your main Thelia composer.json file

```
composer config repositories.cloudipsp git https://github.com/cloudipsp/thelia.git
composer require cloudipsp/thelia
```

### How to use

To use this module, your first need to activate if in the Back-office, tab Modules,
then click on "Configure" on the Alliance bank module line. Enter your Merchant_id, secret_key and save.
