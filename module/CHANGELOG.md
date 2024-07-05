# Change log

## [2.6.3] - 2024-01-21:
### Removed
- Email from enhanced order list view (I think it is unnecessary there and only takes up space).

## [2.6.2] - 2024-01-21:
### Changed
- Admin interface and internals.
### Fixed
- When ordering the same products with different options, only the last added product was in the email.

## [2.6.1] - 2023-11-25:
### Fixed
- Direct order link in the guest order confirmation emails.

## [2.6.0] - 2023-10-20:
### Added
- Order time for admin.
### Internal
- Coding standards updated.

## [2.5.4] - 2023-09-22:
### Changed
- Direct access to the missed orders disabled.
### Fixed
- Minor issues.

## [2.5.3] - 2023-09-16:
### Added
- `Reorder` and `Return` buttons on the direct order view page display for unlogged customers.
- Direct order access link in order status emails.
- Property `target="_blank"` of the direct order link in the admin.
### Fixed
- A minor bug affecting the purchase of vouchers.

## [2.5.2] - 2023-09-14:
### Added
- An ability to disable ordered item pictures in admin emails.

## [2.5.1] - 2023-09-13:
### Fixed
- Twig/HTML markup on admin page to better compatibility with the Twig used in old 3.x OC versions.
- Printing an additional blank page while printing an invoice.
- Minor fixes in the default invoice format.

## [2.5.0] - 2023-09-12:
### Added
- The admin direct access to order invoices without the need to log in using a link from order email.
### Changed
- Direct order access keys generation (the old keys in the emails are now invalid, all others will be updated).
- Now the link for direct order access is only available in customer emails.
### Internal
- Code improvement.

## [2.4.0] - 2023-08-26:
### Added
- Direct access to the order information page by using special links without registration/login.
### Changed
- Module options
### Internal
- Code improvement.

## [2.3.1] - 2023-08-17:
### Fixed
- Merging the same payment and shipping addresses into one cell.
- Compatibility with the country address format from country settings.
### Internal
- Code improvement.

## [2.3.0] - 2023-08-16:
### Added
- Ability to raise the order comment field up.
- Enhanced payment/shipping address in the Latest Order widget
- Order status colors.
### Internal
- Code improvement.

## [2.2.2] - 2023-08-14:
### Changed
- The minimum width of the product name cell is 24 characters.

## [2.2.1] - 2023-07-21:
### Fixed
- Event uninstaller.
### Internal
- Code improvement.

## [2.2.0] - 2023-03-03:
### Added
- Displaying voucher images in orders, the cart, emails.
### Internal
- Minor code fixes and improvements.

## [2.1.4] - 2023-02-28:
### Fixed
- Workaround for product images to display correctly in email (gmail) if filenames contain spaces.
### Changed
- Colspan style for the total cells (long names for total items will now not stretch the quantity column).
- Width of the product column when viewing the order in the customer account - the width will be (3*image_width)px.

## [2.1.3] - 2023-01-21:
### Fixed
- Picture style min-width parameter in the account order view.

## [2.1.2] - 2022-06-02:
### Internal
- Code beautifying.

## [2.1.1] - 2021-11-10:
### Added
- Hide the module on the layouts edit page.
### Internal
- Code refactoring.

## [2.1.0] - 2021-11-10:
### Added
- Fix for "admin/controller/sale/order.php" on line 1800.
### Internal
- Code refactoring.

## [2.0.2] - 2021-01-22:
### Internal
- Code refactoring.

## [2.0.1] - 2020-06-04:
### Added
- Separate image management in emails.

## [2.0.0] - 2020-05-22:
### Changed
- Renamed to Enchaced Orders.
- Admin part fully refactored.
- Partial transition to OpenCart event system.
- Journal 3 compatibility released in a separate addon.
### Internal
- Code refactoring

## [1.2.0] - 2019.11.02:
### Added
- Display product images and links in customer account order history.
### Internal
- Minor code improvements.

## [1.1.0] - 2019.11.01:
### Internal
- Minor code fixes and improvements.

## [1.0.0] - 2019.06.18:
- First release.
