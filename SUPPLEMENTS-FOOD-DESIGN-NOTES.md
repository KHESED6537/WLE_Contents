# 영양제 · 식품 page design

The dedicated page uses the user's supplied Korean content and the visual style established for the return-home shipping page. Its original illustration depicts supplement bottles, tea, biscuits, honey, and an ingredient checklist.

## Files and review

- [Interactive page](supplements-food.html): download and open in a browser; no build or project setup is required.
- [Complete PDF](previews/supplements-food/Worldlink-Supplements-Food-Page.pdf): all content with expanded FAQ answers.
- [Full desktop layout](previews/supplements-food/desktop-full.png) and [full mobile layout](previews/supplements-food/mobile-full.png).
- [Desktop opening screen](previews/supplements-food/desktop-preview.png) and [mobile opening screen](previews/supplements-food/mobile-preview.png).

## Content treatment

Eight sections cover import procedures, supplement quantities, duty-value criteria, general foods, blocked products and ingredients, consultation preparation, five FAQs, and the closing shipping enquiry.

The six-bottle illustration explicitly applies to products classified as health functional foods and combines vitamin 2 + omega-3 2 + probiotics 2. The supplied qualification that being within six bottles does not guarantee clearance or duty exemption is displayed in the same section.

The US$150 panel retains the personal-use and import-condition qualifications. The value table and US$160 explanation preserve the supplied distinction between the duty exemption threshold and the total taxable value. Food-specific honey, walnut, and pine-nut examples remain accompanied by the explanation that a single weight limit does not apply to all food. The supplied livestock prohibition, quarantine requirements, quantity exceptions, ingredient checks, and resale restriction are retained.

The malformed HTML entity `&#xC5D0;` in the supplied text is rendered as the Korean particle `에`.

The text is the user's supplied general guidance; this design task did not independently verify current customs or food-safety regulations. The closing reminder to check rules at purchase and dispatch time is included.

## Navigation and enquiry

The desktop contents menu is sticky. Mobile uses section shortcuts, a collapsible main menu, and a persistent enquiry button. FAQs use native keyboard-accessible disclosure controls. The related-service card opens the existing return-home design in this repository.

Enquiry buttons point to `https://www.worldlinkexp.com/contact`, identified in the supplied audit. The food-safety button uses the exact official URL provided by the user and opens in a new tab. The text reference to 관세청 ‘해외직구 여기로’ is retained without inventing a destination URL. External destinations were not verified from this environment.

## Future site integration

A proposed production route is `/services/supplements-food`. The repository's `supplements-food.html` is a standalone preview, not that deployed route. Confirm the final route and enquiry destination, use approved brand assets, link it from the service listing, and replace the related-service preview URL with the deployed return-home URL.

The page includes full Korean HTML, a unique Korean title and description, Open Graph title/description, and five matching FAQ entries in structured data. The review copy uses `noindex, nofollow`; remove that directive when deploying the approved page, add its canonical and sharing URL/image, and include the route in the site's sitemap. Site-wide server rendering and analytics work described in the audits remains a separate implementation task. Structured data does not guarantee search enhancements.

## Validation

Layout checked at 320, 375, 390, 600, 768, 820, 1024 and 1440 pixels. Verified mobile-menu operation and Escape-key dismissal, section offsets and active contents links, FAQ mouse and keyboard controls, all five FAQ answers against their structured data, table completeness, local related-page navigation, and the presence of key qualifications without JavaScript. The exported PDF is also checked for the main content and unbroken US$150 figure.
