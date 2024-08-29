# Changelog

All notable changes to this project will be documented in this file.

## [2.4.2] - 2024-08-29
[2.1.2]: https://github.com/Smile-SA/elasticsuite-for-retailer/compare/2.4.1...2.4.2

- PHP 8.3 compatibility check

## 2024-05-03

- Map : Fix geolocalize through header button, see https://github.com/Smile-SA/magento2-module-map/compare/2.1.0...2.1.1
- Map : Add CSP whitelist
- Offer : Fix extensionAttribute - Concrete return type must be specified, see https://github.com/Smile-SA/magento2-module-offer/compare/2.0.0...2.0.1
- Retailer : Fix PSR-0, see https://github.com/Smile-SA/magento2-module-retailer/compare/2.0.0...2.0.1
- RetailerOffer : Add modal map to product page search, see https://github.com/Smile-SA/magento2-module-retailer-offer/compare/2.0.1...2.0.2
- RetailerOffer : Fix show product offer price if shop has been selected, even in Retail mode
- StoreDelivery : Refactor - same search design everywhere, see https://github.com/Smile-SA/magento2-module-store-delivery/compare/2.0.0...2.0.1
- StoreDelivery : Dont show store delivery shipping method if no markers found
- StoreLocator : Refactor - same search design everywhere, see https://github.com/Smile-SA/magento2-module-store-locator/compare/2.2.0...2.2.1
- Update contact form

## 2023-09-20

Dataset compatibility Magento 2.4.6, ES 2.11.x and PHP 8.2

- Fix Dynamic type declaration
- Fix Type hinting
- Replace `Zend_Date` by `DateTime`
- Remove `MutationObserver` support
- Fix UI Component Retailer Offer editing
- Replace `Zend_Validate` by `Laminas\Validator`
- Fix Retailer Grid Column Action
- Fix Retailer Grid Mass Actions
- Fix some translations
- Remove Temando/Shipping Plugin
