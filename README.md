# 4662 Crown Parkway — Rental Property Showcase

A single-page website for the rental home at **4662 Crown Parkway, Morrisville, NC 27560**.
Everything lives in one file — `index.html` — with no build step, no dependencies, and
no frameworks. The six tour videos and the floor plan load directly from their Wix URLs.

## What's on the page

1. **Hero** — address, headline, and quick stats (3 bed / 2 bath / sunroom / garage & laundry)
2. **Video tour** — a featured video (kitchen, sunroom & living room) plus five labeled
   video cards in walk-through order: entryway → front bedrooms & shared bath →
   primary suite → laundry & garage → backyard
3. **Floor plan** — click to enlarge in a full-screen lightbox
4. **Home highlights** — six short selling points
5. **Location** — embedded Google Map plus neighborhood copy
6. **Contact** — an "Email the Owner" button

## How to publish it (pick one)

### Option A — GitHub Pages (free, easiest)
1. In this repository on GitHub, go to **Settings → Pages**
2. Under **Build and deployment**, set Source to **Deploy from a branch**
3. Choose your branch and the `/ (root)` folder, then **Save**
4. Your site will be live at `https://<your-username>.github.io/4662/` within a minute or two

### Option B — Any static host
Upload `index.html` to Netlify, Vercel, Cloudflare Pages, or any web host. That one file is the whole site.

### Option C — Inside Wix
In the Wix editor, add an **Embed → Embed HTML** element (full width) and paste the
contents of `index.html`, or link visitors from your Wix site to the hosted page.

## Making edits

Open `index.html` in any text editor:

- **Video titles & descriptions** — search for `tour-card`; each card's `<h3>` and `<p>` are right below its video URL
- **Stats** (beds/baths) — search for `class="stats"`
- **Contact email** — search for `mailto:`
- **Colors** — the palette is defined at the top under `:root` (greens, ivory, brass)
