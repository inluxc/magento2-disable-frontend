## Disable Frontend in Magneto 2
Disable the frontend in Magneto 2 for using only the Admin and the API routes.

#### 1 - Installation Disable Frontend

##### Manual Installation

Install Disable Frontend for Magento2
 * Download the extension
 * Unzip the file
 * Create a folder {Magento root}/app/code/Abelbm/DisableFrontend
 * Copy the content from the unzip folder


##### Using Composer

```
composer require abelbm/magneto2-disablefrontend
```

#### 2 - Enable Disable Frontend

 * php bin/magento module:enable Abelbm_DisableFrontend
 * php bin/magento setup:upgrade
 * php bin/magento cache:flush
 * php bin/magento setup:di:compile