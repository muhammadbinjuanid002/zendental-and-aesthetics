# Zen Dental and Aesthetics — landing page demo

A single-page design preview prepared by **MO Digital** for Zen Dental and Aesthetics.

> This is a design preview. It is not the official website of Zen Dental and Aesthetics,
> and Zen Dental and Aesthetics is not affiliated with MO Digital. The contact details shown
> are the clinic's own public details.

## Live preview

https://zendental-and-aesthetics.vercel.app

## What is in here

| Path | What it is |
|---|---|
| `index.html` | The whole page: markup, inlined CSS and inlined JS in one file |
| `assets/img/` | Photography, cropped WebP, served from this repo (no third-party hotlinking) |
| `assets/fonts/` | Instrument Serif + Inter Tight, subset WOFF2, served from this repo |
| `vercel.json` | Vercel project settings (`outputDirectory: "."`) |

## Design notes

- Dark editorial canvas, cream type, one warm accent per clinic.
- Instrument Serif for display, Inter Tight for interface and body copy.
- Scroll reveal via `IntersectionObserver`; respects `prefers-reduced-motion`.
- Horizontal treatment carousel with a `01 / NN` counter, built in plain JS.
- Mobile-first: the layout is designed at 390px and scales up.
- No framework, no build step, no external requests at runtime.

## Booking

WhatsApp booking on **0311 1199947** - the booking form composes a message with the patient's details.

## Data shown

Clinic name, address, phone number and the Google rating (5.0 stars, 91 reviews) are the clinic's own verified public details. No doctors, prices, testimonials or opening hours have been invented.

---

Design and build by [MO Digital](https://bymo.vercel.app)
