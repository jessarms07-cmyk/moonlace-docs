# Troubleshooting

Use this guide when Moonlace is not behaving as expected.

Before assuming the theme is broken, confirm that you are editing and previewing the correct Moonlace theme copy. Shopify stores have a remarkable talent for making three nearly identical theme copies exist at once.

## My Changes Are Not Appearing

Check:

1. The changes were saved in the theme editor.
2. You are viewing the correct Moonlace theme.
3. You are editing the correct template.
4. You are not previewing an older theme copy.
5. Your browser is not displaying a cached version.
6. The section or block you edited is enabled.
7. The content source you selected still exists.

Try refreshing the storefront or opening it in a private/incognito browser window.

## A Section Is Missing

Check:

- You are editing the correct page template.
- The section has not been removed.
- The section is not hidden or disabled.
- Required products, collections, images, or other content have been selected.
- The section is supported on that template.

To add the section again:

1. Open Shopify admin.
2. Go to **Online Store > Themes**.
3. Click **Customize** beside Moonlace.
4. Open the correct page or template.
5. Click **Add section**.
6. Select the Moonlace section you want.
7. Configure it and save.

## Images Look Cropped or Blurry

Try:

- Uploading a higher-resolution image.
- Using a more suitable image aspect ratio.
- Checking available image-position or focal-point settings.
- Keeping important subjects away from image edges.
- Testing the image on desktop and mobile.

Mobile screens often crop large images differently than desktop screens.

## Text Looks Too Large or Wraps Badly

Check:

- Heading length
- Button text length
- Typography settings
- Custom CSS
- Mobile screen width
- Translated content

Long text may wrap differently across screen sizes and languages.

Shorter headings and button labels often produce better mobile layouts.

## Navigation Looks Wrong

Check:

1. The correct Shopify menu is assigned to the Moonlace Header.
2. Menu links are valid.
3. Nested menu items are structured correctly.
4. Long navigation labels are not causing wrapping.
5. Third-party navigation apps are not replacing Moonlace behavior.

Test both desktop and mobile navigation.

## Mobile Menu Does Not Open

Check:

- You are previewing the correct Moonlace theme.
- Custom JavaScript has not been added recently.
- A third-party app is not modifying the header.
- The browser console does not show JavaScript errors.
- The menu setting is configured correctly.

Test in another browser or private session.

## Search Is Not Working

Check:

1. Products are active.
2. Products are available to the Online Store sales channel.
3. Search terms match available store content.
4. Search-related apps are not replacing Shopify search.
5. The storefront is not showing cached results.

Test:

- Exact product title
- Partial product title
- Broad keyword
- No-results search

## Filters or Sorting Look Incorrect

Check:

- Shopify filtering is configured correctly.
- Product data supports the filters you expect.
- The collection contains visible products.
- Long filter labels are not causing layout issues.
- Custom code or apps are not modifying collection controls.

## A Product Is Missing

Confirm:

- Product is active.
- Product is available to the Online Store sales channel.
- Product is assigned to the expected collection.
- Automated collection conditions are correct.
- Product availability and inventory settings are correct.

## Product Variants Are Not Working

Check:

1. Variants are configured correctly in Shopify.
2. Required variants are available.
3. Inventory permits purchase.
4. The product is active.
5. No app is replacing the product form.
6. Custom JavaScript has not modified variant behavior.

Test the product in an unmodified Moonlace preview if possible.

## Add to Cart Does Not Work

Check:

- Product is available.
- Selected variant is available.
- Inventory permits purchase.
- Required options have been selected.
- Cart-related apps are not interfering.
- Custom JavaScript has not modified the product form.

Try another product to determine whether the issue affects one item or the entire storefront.

## Cart Drawer Does Not Open

Check:

1. The cart drawer is enabled in Moonlace settings.
2. JavaScript is working correctly.
3. Another cart app is not replacing the drawer.
4. Custom code has not modified cart behavior.
5. You are previewing the correct theme.

## Cart Quantity Does Not Update

Check:

- Product availability
- Variant availability
- Inventory
- Cart apps
- Custom code
- Browser cache

Refresh the page and test again.

If the issue can be reproduced in an unmodified Moonlace theme, contact support.

## Cart Count Is Incorrect

Try:

1. Refresh the storefront.
2. Open the cart drawer.
3. Confirm actual cart quantities.
4. Remove or update a product.
5. Test in a private browser session.

If the cart count is only wrong when a third-party app is active, contact the app developer.

## Quick Order Is Empty

Check:

- Products are active.
- Products are available to the Online Store sales channel.
- The selected product source is valid.
- The fallback collection contains visible products.
- The Quick Order section is configured correctly.
- Changes were saved.

## Quick Order Does Not Add Items

Check:

1. Product availability.
2. Variant availability.
3. Inventory.
4. Required options.
5. Cart-related apps.
6. Custom JavaScript.

After adding items, confirm the cart count and cart drawer update correctly.

## Before & After Slider Is Not Working

Check:

- Both images are selected.
- Images are valid and visible.
- Custom CSS is not covering the slider control.
- A third-party script is not interfering with pointer or touch events.
- The issue occurs in more than one browser.

## Countdown Shows the Wrong Time

Check:

1. The configured date.
2. The configured time.
3. Store timezone.
4. Promotion timezone.
5. Daylight-saving differences.
6. Whether the deadline has already passed.

Use genuine merchant-configured dates.

## Age Verifier Does Not Appear

Check:

- It is enabled.
- Theme settings were saved.
- The browser has not already remembered verification.
- You are previewing the correct Moonlace theme.
- Another age-verification app is not replacing it.

Use a new private/incognito browser window to test again.

## Age Verifier Appears Every Time

Check:

- Browser storage settings
- Private browsing
- Cookie/storage restrictions
- Remembered-verification settings
- Apps that clear storefront storage

## Translations Are Missing

Check:

1. The language is published in Shopify.
2. Moonlace is up to date.
3. The missing text belongs to Moonlace rather than an app.
4. Merchant-created content has been translated separately.
5. No raw translation keys are visible.

## RTL Layout Looks Incorrect

Check:

- Active language direction
- Custom CSS
- Apps
- Hardcoded left/right styling
- Directional icons
- Mobile layout

If the issue appears in an unmodified Moonlace theme, contact support.

## Storefront Is Slow

Common causes include:

- Large images
- Too many apps
- Tracking scripts
- Third-party widgets
- Video
- Custom JavaScript
- Large font files
- Excessive homepage content

Try disabling recent app additions and compare performance.

## An App Broke the Layout

If an issue began immediately after installing or changing an app:

1. Temporarily disable the app's storefront integration if possible.
2. Test Moonlace again.
3. Contact the app developer if the issue disappears.
4. Contact Moonlace support if the issue remains in the original theme.

## Custom Code Caused a Problem

If the issue began after editing Liquid, CSS, or JavaScript:

- Restore from a backup if available.
- Remove the recent customization.
- Test the original Moonlace version.
- Contact the developer who added the customization if necessary.

Standard Moonlace support does not guarantee repair of third-party custom code.

## Theme Update Problems

Before updating Moonlace:

- Back up your current theme.
- Review custom code.
- Note app integrations.
- Preview the new version before publishing.

If a customization disappears after an update, it may need to be reapplied manually.

## Still Having Trouble?

Visit [Moonlace Support](support.md) and submit a support request.

Include:

- Store URL
- Moonlace version
- Affected page
- Description
- Steps to reproduce
- Browser
- Device
- Screenshots where useful

Return to the [Moonlace Documentation Home](README.md).
