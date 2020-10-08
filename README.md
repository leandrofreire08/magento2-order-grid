# Magento 2 Module Accolade_OrderGrid

## Functionalities
* Order Grid  UI component customization [added coupon_code, discount_amount columns] 
* Copy [coupon_code, discount_amount] values from sales_order into sales_order_grid table during installation.
* Autocopy [coupon_code, discount_amount] values from sales_order into sales_order_grid table after place new orders.
* Using new feature of data and schema patches available since Magento 2.3 [See docs](https://devdocs.magento.com/guides/v2.3/extension-dev-guide/declarative-schema/data-patches.html).

## Usage 

###### Installation
Install this module into Magento 2 via composer:

    composer require leandrofreire08/magento2-order-grid
    bin/magento module:enable Accolade_OrderGrid
    bin/magento setup:upgrade

###### Uninstall
    bin/magento module:uninstall Accolade_OrderGrid
 
## Demo 
![](https://github.com/leandrofreire08/magento2-order-grid/blob/master/screenshots/demo.gif)
 
## Author
Leandro Freire
