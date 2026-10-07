# English return-home shipping page

The [complete English page](return-home-shipping.html) applies the company's supplied blue/navy/grey colour palette to **이사화물 · 귀국짐**. It is a standalone design preview and needs no installation or build.

## Review

- [Complete page PDF](../previews/en/return-home-shipping/Worldlink-Return-Home-English-Blue.pdf)
- [Full desktop layout](../previews/en/return-home-shipping/desktop-full.png) · [Full mobile layout](../previews/en/return-home-shipping/mobile-full.png)
- [Desktop opening screen](../previews/en/return-home-shipping/desktop-preview.png) · [Mobile opening screen](../previews/en/return-home-shipping/mobile-preview.png)

Download `return-home-shipping.html` and open it in a browser. The Korean-language link opens the existing Korean page when the repository files are kept together. For local development, serve the repository root and visit `/en/return-home-shipping.html`.

## Confirmed colour palette

| Colour | Hex | Main use |
| --- | --- | --- |
| Deep Charcoal / Navy | `#1E202B` | Hero, closing enquiry panel, headings and brand text |
| Electric / Royal Blue | `#2563EB` | Buttons, active navigation, icons and callout accents |
| Soft Cool Grey | `#E5E7EB` | Borders and footer background |

Lighter blue tints support legible text and panels. White content areas separate the long sections. The moving illustration uses blue luggage and light-blue scenery, with natural cardboard and plant colours.

## Complete content retained

The page was generated from the [full English translation](../translations/en/return-home-shipping.md). It retains every source paragraph, heading, table cell and bullet, all five tables, all four FAQ answers, the six-item quotation checklist, the three delivery-scope entries, both original calls to action, and the hypothetical £880 example with its pricing qualification. The English translation and both Korean design files are preserved.

Desktop uses a sticky contents menu. Mobile displays table rows as labelled cards for readability and provides a persistent quotation button. The illustrative cost table keeps the amounts aligned. FAQs use native disclosure controls and matching English structured data. The PDF opens every FAQ and keeps the example pricing table together with its hypothetical-price notice.

## Reference-site limitation

The colours above were explicitly provided by the user. The live Services page at `https://www.worldlinkexp.com/services` could not be inspected because this environment's network proxy blocked it. Its exact logo, typography, spacing and component layout have therefore not been visually verified; the wordmark treatment remains a concept.

The required `www.worldlinkexp.com` access addition was saved to the cloud environment configuration draft. It requires review and saving in Environment settings, followed by publication of the environment, before reference-site inspection can be retried. Publishing that environment configuration is separate from deploying this page to the company website.

## Website integration

A proposed production route is `/en/services/return-home-shipping`. This repository file is a preview, not a deployment to that route. It contains English initial HTML, `lang="en"`, unique English metadata, and four FAQ entries in structured data. The review copy remains `noindex, nofollow`.

For the approved production page, use the confirmed site logo and shared components, confirm the quotation destination, replace the local Korean-page link with its production route, remove the review-only indexing directive, and add the final canonical, sharing metadata, sitemap entry and English/Korean language alternates. No production routes or translation alternates are claimed to exist yet.

## Validation

Checked widths: 320, 375, 390, 600, 768, 820, 1024 and 1440 pixels. Verified no horizontal overflow, exact primary palette values in computed styles, all 120 source blocks and table cells, source table row counts, mobile navigation and Escape-key handling, section offsets and active contents links, keyboard/mouse FAQ controls, structured-data consistency, working local links, and static content without JavaScript. The PDF is checked for all cost amounts and the pricing qualification on the same page as £880.
