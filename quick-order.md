# Quick Order

Moonlace includes a Quick Order section for stores that want customers to add multiple products or quantities efficiently from one place.

Quick Order can be useful for:

- Small catalogs
- Repeat purchases
- Product sets
- Frequently purchased items
- Wholesale-style ordering
- Customers who already know what they want

## Add the Quick Order Section

To add Quick Order:

1. Open Shopify admin.
2. Go to **Online Store > Themes**.
3. Find Moonlace and click **Customize**.
4. Open the page or template where you want Quick Order to appear.
5. Click **Add section**.
6. Select **Quick Order**.
7. Configure the available settings.
8. Save.

## Choose Products

Depending on your Moonlace version and section configuration, Quick Order can display selected products or use a configured collection as a fallback source.

If products do not appear:

1. Confirm the products are active.
2. Confirm they are available to the Online Store sales channel.
3. Confirm the selected collection contains visible products.
4. Review the Quick Order section settings.
5. Save and refresh the preview.

## Quantities

Customers can select quantities for supported products directly within the Quick Order interface.

This allows multiple items to be prepared before submitting them to the cart.

## Add Multiple Items

When customers submit the Quick Order selection, Moonlace uses Shopify cart functionality to add the selected items.

After a successful add:

- Selected products should be added to the cart.
- Quantities should match the Quick Order selections.
- The cart drawer may open depending on the current cart behavior.
- The header cart count should update.
- A success status or message may be announced.

## Cart Drawer Integration

Quick Order is designed to work with the Moonlace cart drawer.

After adding products through Quick Order:

1. Open the cart drawer if it does not open automatically.
2. Confirm each selected item appears.
3. Confirm product quantities are correct.
4. Confirm the cart count matches the current cart contents.
5. Confirm subtotal information updates correctly.

## Product Variants

If products include variants, available variant controls may appear within the Quick Order interface depending on the current product and theme configuration.

Always test:

- Available variants
- Unavailable variants
- Long variant names
- Multiple product selections
- Quantity changes

## Mobile Use

Moonlace is designed so Quick Order remains usable on mobile screens.

When testing mobile Quick Order, check:

- Product names remain readable.
- Variant controls fit within the screen.
- Quantity controls remain accessible.
- Buttons are easy to tap.
- No horizontal overflow occurs.
- Cart interaction works after submission.

## Recommended Testing

Before publishing Quick Order:

1. Add the section to the desired page.
2. Confirm products appear.
3. Select one product.
4. Select multiple products.
5. Change quantities.
6. Add products to the cart.
7. Confirm the success message.
8. Confirm cart count updates.
9. Confirm the cart drawer opens or updates correctly.
10. Test on desktop.
11. Test on mobile.

## If Quick Order Is Empty

If the section appears without products, check:

- Product status
- Online Store availability
- Product or collection selection
- Collection contents
- Theme-editor settings

If a configured product source is unavailable, Moonlace may use the section's configured fallback behavior where supported.

## If Items Do Not Add to Cart

Check:

1. Product availability.
2. Variant availability.
3. Inventory settings.
4. Whether required product options are selected.
5. Whether a cart-related app is interfering with Shopify cart requests.
6. Whether custom JavaScript has modified cart behavior.

## Accessibility

Quick Order is designed to use standard storefront controls and status messaging.

Merchants should still test the final customized storefront for:

- Keyboard navigation
- Visible focus
- Readable labels
- Logical tab order
- Sufficient contrast
- Mobile touch targets

## When Not to Use Quick Order

Quick Order may not be necessary for every store.

It may be less useful when:

- Products require extensive customization.
- Products have many complex options.
- Customers need detailed product information before purchasing.
- The store experience depends heavily on individual product storytelling.

Use Quick Order when it simplifies the shopping journey rather than adding another layer of controls merely because the section exists.

## Next Steps

Continue to [Before & After Slider](before-after.md).

Return to the [Moonlace Documentation Home](README.md).
