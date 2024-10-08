Dawn 15.0.0 adds support for combined listing products and products with over 2,000 variants, includes several enhancements for B2B online stores and localization improvements.

### Commands

shopify theme share

shopify theme pull -d

npx tailwindcss -i ./assets/app-tailwind.css -o ./assets/app.css --watch

shopify theme dev --store stacknyu-101


### Added

- Support for products with over 2,000 variants (when released)
- Support for combined listing products
- Structured data for Product and Article drops generated by new structured_data liquid filter
- Now possible to enable/disable the display of customer avatars via the Shopify admin (without editing code)
- New “Extra Extra Large” font size option for headers

### Changed

- Default values for sections and blocks are now translated in the store's default language
- Optimized CSS to improve rendering performance
- Store policies are now displayed in the footer by default
- Product page, featured product card and cart now display “Duties included” text
- Country selector no longer requires diacritics to match – for example, in French, typing ‘Etats’ will match ‘États-Unis’
- Removed drop shadows from variant images in the quick add modal
- Updated root locale keys of the regional locales to their default variations

### Fixes and improvements

- Implemented client-side validation to better enforce quantity rules
- Fixed an issue where option value selection was incorrect if the user selected an option before fully loading
- Slideshow updated to address irregular movement during scroll
- Fixed an issue where product variant images were not being displayed on mobile
- Fixed an issue where image thumbnail was not updated when a product variant featured media changed
- Improved quantity accuracy when using Quick Order List to add to cart (no longer dropping clicks)
- Quick Order List allows multiple variants to be updated at once
- Quick Add Bulk now displays “out of stock” for items with no inventory
- Improved quantity accuracy when using Quick Add Bulk to add to cart (no longer dropping clicks)
- Significant network performance improvements for Quick Add Bulk
- Product media correctly displayed in the Quick Add Bulk modal when a user selects a variant
- Several UX improvements for Quick Add Bulk modal on desktop
  - Centered "View cart” button text
  - Optimized header and footer spacing
  - Clicking product name now links to the product details page
  - Removed superfluous underlined space on “View full details” link
