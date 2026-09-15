# Pinterest Purity Test

A single-page, client-side quiz built for [PinAtelier](https://pinatelieragency.com) that helps a brand assess how "Pinterest-ready" it is versus how dependent it currently is on short-term social platforms and paid ads.

**Live example:** open `index.html` in any browser — no build step or server required.

## What it does

The quiz walks through 47 yes/no statements grouped into four categories — Pinterest fit, social media dependence, paid ads dependence, and future discovery readiness — and produces a scored result with a written diagnosis and recommendation for each category.

The content is in Ukrainian, targeted at PinAtelier's client base.

## How this was built

The question bank is adapted from a PinAtelier Substack post breaking down Pinterest vs. social-media dependence for brands. Built as an interactive quiz through iterative AI-assisted prototyping, then refined based on real usage feedback: fixed the answer buttons so they hold a consistent position regardless of question length, wired the "work with PinAtelier" call-to-action to email, and confirmed Safari/Chrome compatibility on iPhone 13 and newer.

## Tech

Plain HTML, CSS, and vanilla JavaScript — no frameworks, no dependencies, no build tooling. All quiz logic and copy live in a single `<script>` block in `index.html`.

## Usage

Clone the repo and open `index.html` directly, or serve the folder with any static file server:

```bash
npx serve .
```

## License

MIT — see [LICENSE](LICENSE).
