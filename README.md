# Worldlink Express content designs

A collection of standalone, responsive Korean service-page designs for Worldlink Express. Each page includes its complete content, styles, JavaScript, and illustrations, with no installation or build required.

## 이사화물 · 귀국짐

- [Interactive page](index.html)
- [Complete page design (PDF)](previews/Worldlink-Return-Home-Page.pdf)
- [Desktop page](previews/desktop-full.png) · [Mobile page](previews/mobile-full.png)
- [Desktop opening screen](previews/desktop-preview.png) · [Mobile opening screen](previews/mobile-preview.png)

UK-to-Korea return-home belongings and household shipping, including air/LCL/FCL comparisons, packing and delivery boundaries, customs-exemption qualifications, documents, cost factors, an illustrative £880 calculation, four FAQs, and an enquiry checklist. See [the design notes](DESIGN-NOTES.txt).

## 영양제 · 식품

- [Interactive page](supplements-food.html)
- [Complete page design (PDF)](previews/supplements-food/Worldlink-Supplements-Food-Page.pdf)
- [Desktop page](previews/supplements-food/desktop-full.png) · [Mobile page](previews/supplements-food/mobile-full.png)
- [Desktop opening screen](previews/supplements-food/desktop-preview.png) · [Mobile opening screen](previews/supplements-food/mobile-preview.png)

UK-to-Korea personal-use supplement and food shipping, including import procedures, the combined six-bottle example, duty-value conditions, food-specific criteria, blocked ingredient checks, preparation and packing information, and five FAQs. See [the design notes](SUPPLEMENTS-FOOD-DESIGN-NOTES.md).

## Preview locally

Download either HTML file and open it in a browser to try section navigation, the mobile menu, and expandable FAQs. To download a page from GitHub, use the file's download button or save its raw contents.

For local development, serve this directory:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open `http://127.0.0.1:8000/` for the return-home page or `http://127.0.0.1:8000/supplements-food.html` for the supplements and food page in your own browser.

Both pages use the supplied Korean drafts and SEO audits as design references. Enquiry buttons point to the existing `/contact` route identified in the audit. Each page contains complete Korean HTML, a unique title and description, Open Graph metadata, and matching FAQ structured data. Review prototypes are deliberately marked `noindex, nofollow`.

## Design status

These are design concepts for review. Colours and logo styling are provisional because this environment could not access the live website. The two pages share the cream, teal and terracotta theme. Proposed service routes and production integration considerations are recorded in each page's design notes.

## Validation

Both pages were checked at widths of 320, 375, 390, 600, 768, 820, 1024, and 1440 pixels without horizontal overflow. Mobile navigation, Escape-key handling, section links, active contents navigation, and FAQ mouse/keyboard interactions passed. Full content remains present in static HTML without JavaScript, and the PDFs include expanded FAQ answers.
