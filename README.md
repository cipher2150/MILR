# Myntra Insider Loyalty Revamp

A product case study on redesigning a fashion e-commerce loyalty program so that members shop more often, without raising the discount cost per order.

**Live page:** `https://your-link-here`

## The case in brief

- **Problem:** loyalty rewards feel far away and hard to understand, so most members never move past the entry tier.
- **Idea:** a simple 3-tier ladder based on order count, a visible progress bar, and perks members get immediately.
- **Target users:** shoppers who buy 2 to 4 times a year, the "almost loyal" group.
- **North-star metric:** orders per active member per year.
- **Ask:** approve a gated pilot, starting with 5% of members and a control group.

## What the page covers

| Section | What you will find |
| --- | --- |
| Overview | The whole case in five cards |
| Problem | Five pain points in today's program |
| Goals | North-star, primary and guardrail metrics |
| Users | Three segments and who to focus on |
| Solution | Before and after comparison, tier ladder |
| Journey | A three-month walkthrough for one shopper |
| Rollout | Three phases, two gates, pilot test design |
| Risks | Five risks with mitigations |
| Next steps | Open questions and what happens next |

## Run it locally

No build step and no dependencies. Open the file in a browser:

```bash
open index.html
```

On Windows use `start index.html`, on Linux `xdg-open index.html`.

## Publish it

The site is one static file, so any static host works.

- **Netlify Drop:** drag `index.html` onto the Netlify Drop page.
- **GitHub Pages:** push the file to a repository, then turn on Pages under Settings.
- **Vercel:** import the repository and deploy with the default settings.

## Make it yours

Before publishing, edit these in `index.html`:

1. The author name in the hero (`Your Name`).
2. The email and LinkedIn link in the footer.
3. The page title and description in the `<head>`.
4. Any figure you want to replace with a sourced number.

The colours are CSS variables at the top of the file (`--accent`, `--accent2`, `--bg`, and so on). Change them there and the whole page follows, including dark mode.

## About the numbers

This is an independent case study built for learning and portfolio purposes. It is not affiliated with Myntra and uses no confidential information. Every target, tier threshold and phase length is a planning assumption, and the page says so. In a real project they would be checked against internal data first.

## Features

- Sticky section menu that highlights where you are
- Reading progress bar and back-to-top button
- Works on phones and respects the system dark mode setting
- Prints cleanly to PDF
- Keyboard friendly, with a skip link and visible focus states

## Files

```text
index.html   the full case study (HTML, CSS and a small script)
README.md    this file
```
