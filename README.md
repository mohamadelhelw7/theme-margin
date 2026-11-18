# Margin, a Shopify theme

A premium Online Store 2.0 theme for calm, premium casual wear: linen, knitwear, shirts and trousers. The store is set like a printed catalogue, with white pages, black type and wide margins. Photos are numbered plates with italic captions, and the menu can sit in a quiet rail down the side of the page. It has Arabic and right-to-left support, Egyptian delivery features, and selling tools that usually need apps.

- **Setup guide:** [docs/setup-guide.md](docs/setup-guide.md)
- **دليل الإعداد بالعربية:** [docs/setup-guide.ar.md](docs/setup-guide.ar.md)
- **Changes:** [CHANGELOG.md](CHANGELOG.md)

## Install

- **GitHub (recommended):** Online Store → Themes → Add theme → Connect from GitHub → this repo, `main` branch.
- **Zip:** `shopify theme package` in this folder, then Online Store → Themes → Add theme → Upload zip.
- **Local preview:** `shopify theme dev --store your-store.myshopify.com`

## What's included

**Five style presets:**
- **Margin:** white paper, ink and Caslon italic captions.
- **Linen:** soft off-white, rounded corners and pill buttons.
- **Graphite:** the catalogue in reverse, on near-black.
- **Studio:** Libre Caslon headings.
- **Sage:** sage ink and green accents.

**Margin sections**
- **Margin header:** on computers, a side rail with the logo and an optional line under it, then the menu, then search, account, the bag and the language at its foot.
  - Menu items with sub-links open a panel beside the rail, with the sub-links in columns and an optional image.
  - It can switch to a top bar with a mega menu.
  - Phones get a top bar and a menu drawer.
- **Plate hero:** a video, one photo or two as a spread, set as a catalogue plate with an italic caption.
  - The heading rises line by line, and the photo settles from a slow zoom.
  - Height: full screen, large, medium, adapt to the image, or a chosen aspect ratio.
- **Chapters:** collections set like chapters. Each chapter's title stays pinned while its plates scroll past in a staggered grid.
- **Letters:** customer reviews set like short letters, with a place line, the stars and an italic signature.
- **Margin footer:**
  - A colophon with the store name and a short italic note.
  - Signup and menus beside it.
  - A quiet line with policies, the language selector, social links and payment icons.

**The product page is a catalogue page.**
- **Plates:** the photos are numbered plates with captions taken from each photo's alt text. They stack one under another, or the first runs large and the rest come in pairs.
- **Buying column:** beside the plates and in place as shoppers scroll, with:
  - the collection, name, price and rating;
  - the buying blocks: options, size guide, stock, buy buttons, upsell, back in stock alert, save, delivery timeline, payment icons and WhatsApp;
  - the description and the accordion rows.
- **Phones:** the plates swipe with a counter.

**Product cards** are catalogue plates: the photo, an italic caption with the plate number and type, then the name and price on one line.

**Also included:**
- **Merchandising:** the moving announcement bar, product upsells in three styles, the before and after slider and the delivery timeline.
- **Customer care:** a Customer support section and the Reels video section.
- **Cart:** a cart upsell and an optional free shipping bar, in the drawer and on the cart page.
- **Shared engine:** every section from the shared engine, plus quick view, a sticky add to cart bar and frequently bought together.
- **Store tools:** predictive search, saved items, back in stock alerts and WhatsApp.
- **Egypt and Arabic:** full Arabic with right-to-left layout, and price formats for EGP.

**Technical:**
- Theme blocks everywhere, with no external libraries or remote assets.
- Bundled fonts: Schibsted Grotesk and Libre Caslon Text, with Vazirmatn for Arabic.
- Effects only run on screen and turn off for visitors who prefer reduced motion.

## Versioning

`theme_version` in `config/settings_schema.json` goes up with every change, and `shopify theme package` names the zip after it.
