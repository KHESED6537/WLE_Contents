# Worldlink Express content designs

A standalone, responsive Korean page concept for **서비스 → 이사화물 · 귀국짐**: shipping return-home belongings and household goods from the UK to Korea.

## View the design

- [Complete page design (PDF)](previews/Worldlink-Return-Home-Page.pdf)
- [Desktop page](previews/desktop-full.png) · [Mobile page](previews/mobile-full.png)
- [Desktop opening screen](previews/desktop-preview.png) · [Mobile opening screen](previews/mobile-preview.png)

Download [index.html](index.html) and open it in a browser to try the section navigation, mobile menu, and expandable FAQs. The HTML includes all styles, JavaScript, and illustrations; no installation or build is required.

For local development, serve this directory:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open `http://127.0.0.1:8000/` in your own browser.

## Included content

The page uses the supplied Korean draft and SEO audits as design references. It includes air/LCL/FCL comparisons, packing and delivery boundaries, customs-exemption qualifications, required documents, cost factors, an illustrative £880 calculation, four FAQs, and an enquiry checklist. Enquiry buttons point to the existing `/contact` route identified in the audit.

The page contains complete Korean HTML, a unique title and description, Open Graph metadata, and FAQ structured data. The review prototype is deliberately marked `noindex, nofollow`.

## Design status

This is a design concept, not a deployment to the company website. Colours and logo styling are provisional because this environment could not access the live website. See [the design notes](DESIGN-NOTES.txt) for the proposed service-page route and production integration considerations.

## Validation

The source was checked at widths of 320, 375, 390, 600, 768, 820, 1024, and 1440 pixels without horizontal overflow. Mobile navigation, Escape-key handling, section links, active contents navigation, and FAQ mouse/keyboard interactions passed. The full content remains present in static HTML without JavaScript. The PDF includes all seven content sections and expanded FAQ answers.
