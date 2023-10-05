# Extend_EEAdmin
Custom Add on for Magento EE compatibility with Extend's warranty module (v2.x)

This module fixes the "Add Products By SKU" button missing from magento 2 Enterprise Edition in the admin area/order/new order, when Extend_Warranty is installed.

## To install :

copy contents into app/code/Extend, so you would end up with app/code/Extend/EEAdmin
then run :
- ``bin/magento module:enable Extend_EEAdmin``
- ``bin/magento setup:upgrade``
- ``bin/magento setup:di:compile``
- ``bin/magento cache:clean``

- 
