# Cart & Cart Drawer

Moonlace includes both standard Shopify cart functionality and a responsive cart drawer designed to keep shopping interactions fast and easy.

## Cart Drawer

The cart drawer allows customers to review and update their cart without leaving the page they are currently browsing.

Depending on the cart contents and store configuration, customers can:

- Review products
- Change quantities
- Remove products
- Review variant information
- Add cart notes where supported
- Review subtotal information
- Continue to checkout

## Opening the Cart Drawer

The cart drawer opens when customers interact with supported cart controls or add products through supported Moonlace shopping features.

The exact behavior may vary depending on the current Moonlace settings and storefront configuration.

## Updating Quantities

Customers can adjust product quantities directly in the cart drawer.

Moonlace updates Shopify cart data and keeps the visible cart count synchronized with the current cart contents.

## Removing Products

Products can be removed using the available cart controls.

After removal:

- Cart contents should update
- Subtotal should update
- Header cart count should update
- Empty-cart messaging should appear when appropriate

## Multiple Products and Variants

Moonlace supports carts containing:

- Multiple products
- Multiple quantities
- Different variants
- Products with long titles
- Products with long variant names

Always test your own catalog because product names and option combinations can affect layout.

## Mobile Cart Drawer

Moonlace is designed so the cart drawer remains usable on smaller screens.

On mobile:

- Cart items can scroll when needed
- Important controls remain reachable
- Checkout remains accessible
- Product content adapts to narrower widths

Test the final cart experience on mobile after installing apps or adding custom code.

## Cart Page

Moonlace also supports the standard Shopify cart page.

Depending on your setup, the cart page may include:

- Product images
- Product titles
- Variant information
- Quantity controls
- Remove links
- Cart notes
- Subtotal
- Update Cart button
- Checkout button

## Cart Notes

Where enabled, cart notes allow customers to add information to the order before checkout.

Common uses include:

- Gift notes
- Delivery instructions
- Order requests
- General customer notes

Do not use cart notes to collect sensitive payment or security information.

## Checkout

Moonlace does not replace Shopify Checkout.

When customers click Checkout, they continue into Shopify's checkout experience according to the merchant's Shopify plan and store configuration.

## Cart Count

The cart count shown in the storefront header reflects the current Shopify cart quantity.

If the cart count appears incorrect:

1. Refresh the storefront.
2. Confirm the cart update completed successfully.
3. Test in a private or incognito browser window.
4. Check whether a cart-related app is modifying Shopify cart behavior.
5. Test without recently added custom cart code if appropriate.

## Cart Apps

Third-party apps can modify cart behavior.

Examples include:

- Upsell apps
- Bundle apps
- Gift apps
- Shipping apps
- Discount apps
- Subscription apps
- Cart drawer replacements

If cart problems begin after installing an app, test whether the problem remains when that app's storefront integration is disabled.

## Testing the Cart

Before publishing Moonlace, test:

1. Add one product.
2. Add multiple products.
3. Add multiple variants.
4. Change quantities.
5. Remove an item.
6. Empty the cart.
7. Add products again.
8. Open and close the cart drawer.
9. Review subtotal.
10. Continue to checkout.
11. Test on mobile.
12. Test long product and variant names.

## Empty Cart

When no products remain, Moonlace displays the appropriate empty-cart state.

If an empty cart does not display correctly:

- Refresh the page
- Confirm the cart is actually empty
- Test without cart-related apps
- Test in a private browser session

## Troubleshooting

### Quantity Is Not Updating

Check:

- Product availability
- Variant availability
- Inventory settings
- Cart-related apps
- Custom storefront code
- Browser cache

### Cart Drawer Does Not Open

Check:

1. You are previewing the correct Moonlace theme.
2. The relevant cart settings are enabled.
3. JavaScript has not been broken by custom code.
4. A third-party app is not replacing the cart experience.

### Checkout Button Is Missing

Confirm:

- Cart contains purchasable products.
- Products and variants are available.
- The correct cart template is being used.
- Third-party cart code is not altering the drawer or page.

## Next Steps

Continue to [Quick Order](quick-order.md).

Return to the [Moonlace Documentation Home](README.md).
