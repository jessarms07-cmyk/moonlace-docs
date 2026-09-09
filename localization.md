# Localization & RTL

Moonlace includes built-in theme locale support for multiple languages and includes right-to-left layout support for stores using RTL languages.

Current Moonlace theme locale support includes:

- English
- French
- German
- Italian
- Spanish

## What Theme Localization Does

Theme localization translates supported interface text provided by Moonlace, such as:

- Buttons
- Labels
- Cart text
- Search text
- Navigation-related text
- Product interface text
- Theme messages
- Other built-in storefront wording

Localization files control theme interface text only.

## What Moonlace Does Not Automatically Translate

Merchant-created content may still require translation.

This can include:

- Product titles
- Product descriptions
- Collection descriptions
- Pages
- Blog posts
- Navigation menus
- Store policies
- Custom section text
- Custom Liquid content

Use Shopify's translation tools or another compatible translation workflow for merchant-created content.

## Configure Store Languages

Language configuration is managed through Shopify.

To review or add store languages:

1. Open Shopify admin.
2. Go to your store's language or market settings.
3. Add or configure the languages you want to support.
4. Publish the appropriate translations.
5. Preview the storefront in each language.

The exact Shopify menu location may vary as Shopify updates its admin interface.

## Test Each Language

After enabling a language, review:

- Header
- Navigation
- Search
- Product pages
- Collection pages
- Cart drawer
- Cart page
- Quick Order
- Footer
- Specialty sections
- Buttons
- Form labels
- Error and status messages

Check for:

- Missing translations
- Raw translation keys
- Text overflow
- Truncated buttons
- Awkward line wrapping
- Layout changes caused by longer translated text

## Longer Translations

Some languages require more space than English.

For example, a short English button label may become significantly longer after translation.

When testing translated storefronts:

- Review narrow mobile widths.
- Check button wrapping.
- Check navigation labels.
- Review product-card spacing.
- Review form labels.
- Confirm cart controls remain usable.

## Right-to-Left Support

Moonlace includes RTL-ready presentation for languages that use right-to-left reading direction.

Examples of RTL languages include Arabic and Hebrew.

When the active storefront locale uses right-to-left direction, Moonlace can adapt layout direction accordingly.

## What Changes in RTL Layouts

RTL presentation may affect:

- Text alignment
- Navigation direction
- Menu layout
- Cart drawer direction
- Product cards
- Form controls
- Directional icons
- Sliders
- Buttons
- Spacing
- Breadcrumbs
- Other directional interface elements

## Test RTL Presentation

If your store uses an RTL language, review the complete storefront in that language.

Test:

1. Homepage
2. Header
3. Main navigation
4. Mobile navigation
5. Product pages
6. Collection pages
7. Search
8. Cart drawer
9. Cart page
10. Quick Order
11. Before & After Slider
12. Countdown
13. Age Verifier
14. Footer

## Directional Icons

Some icons may need to visually reverse direction in RTL layouts.

Examples include:

- Arrows
- Previous/next controls
- Drawer direction
- Breadcrumb indicators

If a directional control appears incorrect in RTL mode, report it through Moonlace support.

## Third-Party Apps

Apps may not automatically follow Moonlace's RTL or localization behavior.

Third-party apps can introduce:

- Hardcoded English text
- Left-to-right-only layouts
- Incorrect alignment
- Untranslated labels
- Directional icons that do not reverse
- Layout overflow

If an RTL or translation issue occurs only inside an app, contact that app's developer.

## Custom Code

Custom Liquid, CSS, or JavaScript may affect localization and RTL behavior.

When adding custom code:

- Avoid hardcoding English text when translation support is needed.
- Prefer logical CSS properties where possible.
- Test both left-to-right and right-to-left layouts.
- Review mobile presentation.

## Missing Translation Text

If you see a raw translation key or missing text:

1. Confirm the correct language is published.
2. Confirm Moonlace is up to date.
3. Check whether the text belongs to Moonlace or a third-party app.
4. Test in the original Moonlace theme without custom code.
5. Report the issue to Moonlace support if it can be reproduced in the theme.

## Translation Quality

Moonlace provides theme locale support, but merchants should review storefront translations before launch.

Translation quality can depend on:

- Store content
- Product terminology
- Brand language
- Industry-specific wording
- Regional differences

Review important customer-facing text manually when possible.

## Accessibility and Localization

When translating storefront content:

- Keep button labels understandable.
- Avoid unclear abbreviations.
- Maintain readable contrast.
- Use meaningful headings.
- Keep form instructions clear.
- Check keyboard navigation after layout changes.
- Test screen-reader-relevant labels where applicable.

## Recommended Localization Checklist

Before launching a translated storefront:

1. Publish the language in Shopify.
2. Review the homepage.
3. Review navigation.
4. Test search.
5. Open several products.
6. Open several collections.
7. Test Add to Cart.
8. Test the cart drawer.
9. Test Quick Order if enabled.
10. Review specialty sections.
11. Review policies.
12. Review mobile layouts.
13. Confirm no raw translation keys appear.
14. Test RTL visually if applicable.

## Troubleshooting

### Some Text Is Still in English

Check whether the text belongs to:

- Moonlace
- Merchant-created content
- A Shopify system area
- A third-party app

Theme locale files cannot translate every type of Shopify store content automatically.

### Layout Breaks in Another Language

Check:

- Long translated labels
- Custom CSS
- Apps
- Fixed-width elements
- Mobile widths
- Custom code

### RTL Layout Looks Incorrect

Test the issue in an unmodified Moonlace preview.

If the problem remains in the original theme, submit a support request with:

- Store URL
- Active language
- Affected page
- Screenshot
- Device
- Browser

## Next Steps

Continue to the [FAQ](faq.md).

Return to the [Moonlace Documentation Home](README.md).
