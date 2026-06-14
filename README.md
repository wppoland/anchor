# Anchor

Anchor adds a slim, sticky add-to-cart bar to your WooCommerce single product pages. It stays hidden until the shopper scrolls past the main add-to-cart form, then slides into view with the product thumbnail, title, price, an optional quantity field and a buy button — keeping the purchase one tap away on long pages.

## Features

- Sticky add-to-cart bar revealed on scroll, positioned at the top or bottom of the screen.
- Show or hide on desktop and mobile independently, with a configurable scroll threshold.
- Optionally show the product thumbnail, price and quantity field.
- Variation-aware: on variable products the bar mirrors WooCommerce's native variations form, keeping price, availability and the buy button in sync. No jQuery of its own.
- Fixed to the viewport and starts hidden, so it causes zero Cumulative Layout Shift.
- Accessible region with keyboard support, visible focus and screen-reader text; respects reduced-motion and dark mode.

## Installation

1. Upload the plugin to `/wp-content/plugins/anchor`, or install it from Plugins → Add New.
2. Activate it. WooCommerce must be active.
3. Go to WooCommerce → Anchor to choose the position, devices, scroll threshold and which elements appear.

## Frequently Asked Questions

**Does it work with variable products?**
Yes. The bar mirrors WooCommerce's native variations form, so its price, availability and buy button update as the shopper picks options.

**Will it slow my product pages down or shift the layout?**
No. Assets load only on single product pages, and the bar is fixed and hidden until needed, so it never causes layout shift.

Built by WPPoland — https://plogins.com

License: GPL-2.0-or-later
