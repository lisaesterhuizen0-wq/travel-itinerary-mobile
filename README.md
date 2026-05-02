# Travel Itinerary — Mobile View

A mobile-first single-page travel itinerary, built as part of a RAY AI bootcamp exercise.

**Live demo:** https://lisaesterhuizen0-wq.github.io/travel-itinerary-mobile/

## Why I built this

The bootcamp brief was to design something an executive assistant might hand a busy traveller: an at-a-glance itinerary that loads instantly on a phone, with no app to install. I focused on layout-first thinking — what does the traveller need to see in five seconds, and what can wait until they tap?

## What's in this repo

- `index.html` — a self-contained page (HTML + inline React via CDN, no build step). Trip data lives in a config object near the top, so the itinerary can be retargeted by editing one block.

## Tech

- HTML
- React 18 (loaded inline via CDN — no build tooling)
- Hand-rolled CSS, mobile-first

## How to view locally

Open `index.html` in any browser, or visit the live demo link above.

## Notes

The traveller is shown as `Sample Traveller` and the trip data is placeholder. Swap them in the config block near the top of `index.html` to retarget to a real trip.

---

*Part of my AI Operations portfolio — github.com/lisaesterhuizen0-wq*
