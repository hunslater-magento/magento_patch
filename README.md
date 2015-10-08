MMind_Magento_Patch
==================
Unofficial patch to fix Mage_Catalog_Model_Url class.
This patch avoid to create infinite loop url for product with the same url key.
Create a copy on local magento pool of the class Mage_Catalog_Model_Url and then apply the path via phpstorm

# Patch Branch
- product-url

# Magento Version 
- 1.7.x
- 1.8.x
- < 1.9.2.0