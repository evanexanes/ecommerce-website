# E-commerce Store (OneStopShop): documentation

This repository is a static export of a WordPress practice site, hosted on GitHub Pages at
<https://evanexanes.github.io/ecommerce-website/>. It holds generated HTML, CSS and JavaScript only: there is no
PHP, database or `wp-config.php`. See the [README](../README.md) for the overview and licence.

## Stack

| Part | Tool |
|---|---|
| CMS | WordPress |
| Shop | WooCommerce |
| Page builder | Elementor (Pro Elements) |
| Theme | Hello Elementor |

## Theme and plugins in the export

- Theme: `hello-elementor`
- Plugin folders under `wp-content/plugins/`: `all-in-one-wp-migration`, `custom-post-type-ui`, `elementor`, `pro-elements`, `pymntpl-paypal-woocommerce`, `simply-static`, `themify-wc-product-filter`, `woocommerce`

These are third-party WordPress files under their own GPL licences and are not edited by hand.

## Pages

Every page below opens with a documentation header: program name, description, author and a
history table. 72 pages.

| File | Page title |
|---|---|
| `author/ecommerce/index.html` | ecommerce |
| `author/myselfvsme7/index.html` | Redirecting... |
| `cart/index.html` | Cart |
| `category/uncategorized/index.html` | Uncategorized |
| `checkout/index.html` | Redirecting... |
| `custom-thank-you-page/index.html` | Custom Thank you page |
| `hello-world/index.html` | Hello world! |
| `index.html` | OneStopShop |
| `my-account/index.html` | My account |
| `order-tracking/index.html` | Order Tracking |
| `privacy-policy-2/index.html` | Privacy Policy |
| `product-brand/apple/index.html` | Apple |
| `product-brand/chanel/index.html` | Chanel |
| `product-brand/christian-dior/index.html` | Christian Dior |
| `product-brand/creed/index.html` | Creed |
| `product-brand/giorgio-armani/index.html` | Giorgio Armani |
| `product-brand/jackjones/index.html` | Jack&Jones |
| `product-brand/microsoft/index.html` | Microsoft |
| `product-brand/tom-ford/index.html` | Tom Ford |
| `product-category/clothing/accessories/index.html` | Accessories |
| `product-category/clothing/bottoms/index.html` | Bottoms |
| `product-category/clothing/index.html` | Clothing |
| `product-category/clothing/shirts/index.html` | Shirts |
| `product-category/clothing/shoes/index.html` | Shoes |
| `product-category/electronics/desktop/index.html` | Desktop |
| `product-category/electronics/index.html` | Electronics |
| `product-category/electronics/laptops/index.html` | Laptops |
| `product-category/electronics/mobile/index.html` | Mobile |
| `product-category/fragrance/aquatic/index.html` | Aquatic |
| `product-category/fragrance/citrus/index.html` | Citrus |
| `product-category/fragrance/index.html` | Fragrance |
| `product-category/fragrance/spicy-fragrance/index.html` | Spicy |
| `product-category/fragrance/woody/index.html` | Woody |
| `product-tag/men-collection/index.html` | Men Collection |
| `product-tag/office-collection/index.html` | Office Collection |
| `product-tag/women-collection/index.html` | Women Collection |
| `product/201/index.html` | Shoes for men |
| `product/apple-vision-pro/index.html` | Apple Vision Pro |
| `product/apple-watch-ultra/index.html` | Apple Watch Ultra |
| `product/aqua-di-gio-profumo/index.html` | Aqua Di Gio Profumo |
| `product/bleu-de-channel-edt/index.html` | Bleu De Channel edt |
| `product/creed-aventus/index.html` | Creed Aventus |
| `product/dior-sauvage-elixir/index.html` | Dior Sauvage Elixir |
| `product/hp-omen-laptop/index.html` | HP Omen Laptop |
| `product/jeans-for-men/index.html` | Jeans For Men |
| `product/mac-studio/index.html` | Mac Studio |
| `product/macbook-pro/index.html` | MacBook Pro |
| `product/microsoft-surface-pro/index.html` | Microsoft Surface Pro |
| `product/monkstrap-shoes/index.html` | Monkstrap Shoes |
| `product/necklace-for-men/index.html` | Necklace for men |
| `product/oud-wood-by-tom-ford/index.html` | Oud wood by tom ford |
| `product/pajamas-for-women/index.html` | Pajamas for Women |
| `product/plain-polo-shirt-for-men/index.html` | Plain Polo Shirt for Men |
| `product/pro-display-xdr/index.html` | Pro Display XDR |
| `product/shirt-polo-men/index.html` | Shirt Polo Men |
| `product/shoes-for-men-monks/index.html` | Shoes for men Monks |
| `product/skirt-denim/index.html` | Skirt Denim |
| `product/skirt/index.html` | Skirt |
| `product/tshirt-for-men/index.html` | Tshirt for men |
| `product/tshirt-for-women/index.html` | Tshirt for women |
| `product/type-c-apple-airpods/index.html` | Type C Apple Airpods |
| `product/watch-for-men/index.html` | Watch For Men |
| `product/watch-for-women/index.html` | Watch for Women |
| `product/women-bracelet/index.html` | Women Bracelet |
| `product/women-earrings/index.html` | Women Earrings |
| `product/yellow-shirt-for-men/index.html` | Yellow Shirt for men |
| `refund-and-returns-policy/index.html` | Refund and Returns Policy |
| `sample-page/index.html` | Sample Page |
| `shop/index.html` | Shop |
| `shop/page/2/index.html` | Shop |
| `shop/page/3/index.html` | Shop |
| `terms-and-conditions/index.html` | Terms and Conditions |

## Changing the site

1. Edit the page in WordPress.
2. Export the site again with Simply Static and replace the generated files.
3. A re-export overwrites the pages and removes their headers. Put the header back and add a history
   row with the date, a description of 32 characters or fewer, and `EPPE`.

## Images

The pictures under `wp-content/uploads/` are WebP files named after the original, for example
`featured-3.png.webp`, and every page points at them. This cut the home page from about 4.3 MB to
0.9 MB. Four small images stayed PNG because WebP was not clearly smaller. Files inside
`wp-content/plugins/` and the theme are third-party and were left as they were. A re-export from
WordPress brings the original PNG and JPEG files back, so convert them again after exporting.

## Change history

| Date | Description | Programmer name |
|---|---|---|
| 09/28/2026 | Initial Implementation | EPPE |
| 11/10/2026 | Added file headers and docs | EPPE |
| 11/10/2026 | Converted images to WebP | EPPE |
