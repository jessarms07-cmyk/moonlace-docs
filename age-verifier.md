# Age Verifier

Moonlace includes an optional Age Verifier for stores that need visitors to confirm an age requirement before entering the storefront.

The Age Verifier is optional and should only be enabled when it is appropriate for the products, audience, or legal requirements of the store.

## Enable the Age Verifier

To enable the Age Verifier:

1. Open Shopify admin.
2. Go to **Online Store > Themes**.
3. Find Moonlace and click **Customize**.
4. Open the relevant Moonlace Age Verifier settings.
5. Enable the verifier.
6. Configure the available message and options.
7. Save.

## Configure the Message

Use clear wording so visitors understand what they are confirming.

The exact text should reflect your store and applicable requirements.

Possible message elements may include:

- Age requirement
- Entry confirmation
- Exit or decline option
- Supporting legal or policy text
- Store-specific information

Avoid vague wording that leaves visitors unsure what they are confirming.

## Remembered Verification

Moonlace can remember a visitor's successful verification according to the feature's configured behavior.

This prevents the verifier from appearing repeatedly during the same remembered period.

When testing remembered behavior, you may need to:

- Open a private or incognito browser window
- Clear browser storage
- Use a different browser
- Start a new private session

## Test the Age Verifier

After enabling it:

1. Open the storefront in a private or incognito browser window.
2. Confirm the verifier appears.
3. Review the message.
4. Complete the verification.
5. Navigate through the storefront.
6. Refresh the page.
7. Confirm remembered verification behaves as expected.
8. Test the decline or exit behavior if enabled.
9. Test on desktop.
10. Test on mobile.

## Mobile Use

On mobile, confirm:

- The verifier fits within the screen.
- Text remains readable.
- Buttons are easy to tap.
- The close or exit control remains reachable where applicable.
- No content is cut off.
- The verifier can scroll if necessary.
- Background content does not interfere with the dialog.

## Accessibility

When using the Age Verifier:

- Keep text readable.
- Use clear button labels.
- Maintain sufficient color contrast.
- Make sure controls are keyboard accessible.
- Keep focus within the verifier while it is active where appropriate.
- Ensure visitors can understand the available choices.
- Do not rely only on color to communicate meaning.

## Legal Responsibility

The Moonlace Age Verifier provides storefront functionality only.

It does not guarantee legal or regulatory compliance.

Merchants are responsible for determining:

- Whether age verification is required
- What age threshold applies
- What wording is required
- Whether additional verification methods are necessary
- Whether their products may legally be sold online
- Whether additional regional restrictions apply

Consult appropriate legal or regulatory guidance for your business when necessary.

## Restricted Products

Enabling the Age Verifier does not override Shopify policies or applicable laws.

Merchants remain responsible for ensuring that products sold through their store are permitted by:

- Shopify
- Payment providers
- Shipping carriers
- Applicable laws
- Local regulations

## Troubleshooting

### The Age Verifier Does Not Appear

Check:

1. The feature is enabled.
2. You saved the theme settings.
3. You are previewing the correct Moonlace theme.
4. Your browser has not already stored a successful verification.
5. Test in a new private or incognito window.

### The Verifier Appears Every Time

Check:

- Browser storage settings
- Private browsing mode
- Cookie/storage restrictions
- Whether remembered verification is enabled
- Whether another app is clearing storefront storage

### Buttons Do Not Work

Check:

1. Custom JavaScript has not modified the verifier.
2. Another popup or age-verification app is not conflicting with Moonlace.
3. The storefront has no JavaScript errors.
4. Test in another browser.

### The Verifier Is Cut Off on Mobile

Check:

- Mobile browser zoom
- Custom CSS
- Third-party popup apps
- Long custom text
- Large button labels

Try shortening custom content and testing again.

## Using Other Age Verification Apps

If you install a third-party age-verification app, consider disabling Moonlace's built-in Age Verifier to avoid:

- Duplicate verification screens
- Conflicting overlays
- Focus problems
- Repeated prompts
- Mobile layout conflicts

Use one primary age-verification experience unless you have a specific reason to do otherwise.

## Recommended Use

Use the Age Verifier only when it serves a legitimate purpose for the store.

Adding barriers to entry for decoration is a fairly inventive way to annoy customers before they have even seen a product.

## Next Steps

Continue to [Localization & RTL](localization.md).

Return to the [Moonlace Documentation Home](README.md).
