Magento 2 Norwegian Language Pack (nb_NO)



Configure Magento backend

Activate language (backend): Account > Settings > Account information > Interface Locale
Activate language (frontend): Stores > Settings > Configuration > [storeview] > Locale options > Locale



Installation (manual)

Clone repository to app/i18n/cosnip/nb_no/
Upgrade Magento installation $ php bin/magento setup:upgrade
Clear Magento cache$ php bin/magento cache:clean
Deploy Static Content $ php bin/magento setup:static-content:deploy nb_NO



Installation (Composer)

Require via Composer CLI $ composer require cosinp/nb_NO
Upgrade Magento installation $ php bin/magento setup:upgrade
Clear Magento cache$ php bin/magento cache:clean
Deploy Static Content $ php bin/magento setup:static-content:deploy nb_NO
