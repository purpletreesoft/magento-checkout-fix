# magento-checkout-fix
Fixes "Checkout out as a new customer" and "Checkout out using your account" for Magento 2.

For popup login in Magento 2, this extension replaces strings "Checkout out as a new customer" and "Checkout out using your account" with "Checkout as a new customer" and "Checkout using your account" respectively.

This is such a small issues that it should have been fixed in magento long ago, but unfortunately it still persists from Magento 2.0 till Magento 2.2.3.

# Installation

1. Download the source code as a zip file and extract it in app/code directory.

2. Run follwowing command from installation root directory on shell:

bin/magento setup:upgrade 
