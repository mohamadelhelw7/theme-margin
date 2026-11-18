# Margin setup guide

Margin sets a casual wear store like a printed catalogue: white pages, black type, wide margins, and photos as numbered plates with italic captions. This guide takes you from install to a store that's ready to sell. Setting names are written as they appear in the theme editor.

## 1. Install

- **From GitHub**: go to **Online Store → Themes → Add theme → Connect from GitHub** and pick the repository and the `main` branch. Changes pushed to `main` show up automatically.
- **From a zip**: go to **Online Store → Themes → Add theme → Upload zip file**.

If a change doesn't show up on a GitHub-connected theme, open the theme card, click **View logs**, then **Actions → Reset to last commit**.

## 2. Pick a style

Go to **Customize → Theme settings → Theme styles**. You can change anything afterwards.

| Style | Look |
| --- | --- |
| Margin | White paper, ink, Schibsted Grotesk headings and Caslon italic captions |
| Linen | Soft off-white, rounded corners and pill buttons |
| Graphite | The catalogue in reverse, on near-black |
| Studio | Libre Caslon headings with italic accent words |
| Sage | White with sage ink and green accents |

## 3. Colors

**Theme settings → Colors** has six color schemes. In the Margin style:

| Scheme | Color | Used for |
| --- | --- | --- |
| 1 | White | The page |
| 2 | Light grey | The statement, the videos, the newsletter and the FAQ |
| 3 | Near-black | Free to use |
| 4 | Stone | Free to use |
| 5 | White with a red accent | Free to use |
| 6 | Black | Free to use |

**Image tints** are the colors behind product photos. **Theme settings → Lines and grid** can add thin lines between product cards and under section headings. Margin keeps them off by default.

## 4. Fonts and captions

- **Fonts**, in **Theme settings → Typography**:
  - **Heading font**: Schibsted Grotesk or Libre Caslon, or any font from Shopify's library.
  - **Body font**: Schibsted Grotesk, or any library font.
  - **Arabic**: Vazirmatn for headings and text. It only loads when a page shows Arabic.
- **Accent words**: wrap words in *asterisks*, for example `Clothes for the *quiet* days`. **Accent words in headings → Caslon italic** sets them in italic Caslon. They can also be underlined, plain italic or in the accent color.
- **Theme settings → Catalogue**:
  - **Captions**: Caslon italic (the default) or the body text.
  - **Word before plate numbers**: Plate by default, for example Plate 07. Write No. or Look if you prefer, and translate it with Translate & Adapt.
  - **Side rail width**: from 160 to 280 pixels.

## 5. Announcement bar

The announcement bar moves as a ticker with a thin line under it. Edit the messages in **Customize → Announcement bar**. **Speed** is in pixels per second, and **Mode** switches it to rotating or static.

## 6. Header

**Customize → Header** uses the **Margin header**.

- **Layout on computers → Side rail** (the default):
  - The menu sits in a quiet rail down the left of the page (the right in Arabic), with your logo and an optional **Line under the logo** at the top.
  - Search, account, the bag and the language selector sit at its foot.
- **Top bar**: puts everything in a bar across the top instead.
- **Menus with sub-links**:
  - In the side rail, a menu item with sub-links opens a panel beside the rail, with the sub-links in columns. Add a **Menu panel image** to show a photo in it.
  - In the top bar, **Dropdown style → Mega menu** does the same in a full-width panel.
  - Create the menu in **Online Store → Navigation**.
- **Phones** always get a top bar with the menu, logo, search and bag. The menu drawer holds the links, the account, WhatsApp, and the language and country.
- **Show language selector on desktop** is on. It appears once you add a second language in **Settings → Languages**.

## 7. Homepage

The homepage has ten sections. Each one can be moved, hidden or removed.

### Plate hero

- **Layout**: the photo beside the text (the default) or above it. **Photo position** puts the photo at the start or the end.
- **Photo or video**:
  - One **Image**, two images side by side as a spread (**Second image**, stacked on phones), or a **Video** that plays muted on a loop.
  - **Phone image** replaces the images on phones.
- **Height**: full screen, large or medium.
  - **Adapt to the image or video** gives the photo its own shape, so the whole image shows.
  - **Aspect ratio below** uses **Aspect ratio**, from 21:9 to 2:3, with its own **Aspect ratio on phones**.
- **Caption under the photo** and **Caption at the end** are set in italics, like a catalogue plate.
- The heading rises line by line, and the photo settles from a slow zoom.

### New arrivals

Products in a slider with tabs: newest, all and on sale. Each card is a catalogue plate with its number and type.

### Chapters

Collections set like chapters in a catalogue. Each chapter's number and title stay pinned on one side while its plates scroll past in a staggered grid. On phones the plates swipe.

- Add a **Chapter** block for each collection and pick the collection. **Plates** sets how many products show, from 2 to 8.
- The chapter's text comes from the block, or from the start of the collection description.
- **Word before chapter numbers** (Chapter by default), **Plates per row on desktop** and **Keep the title in place** are in the section settings.

### From the studio

A short statement that lights up word by word as shoppers scroll.

### Before and after

Compare two photos of the same piece, for example plain and styled. Shoppers drag the line between them.

### Letters

Customer reviews set like short letters: a place or date line, the stars, the review and an italic signature with the product they reviewed. Paste real reviews only, one per **Letter** block.

### Worn by you

The **Reels** section: short vertical videos from your customers or your shoots.

- In each **Reel** block, upload a video (9:16 works best, under **Content → Files**) and a cover image.
- Add a caption, such as the customer's handle with their permission, and the product in the video.

### Journal, Customer support and Newsletter

- **Journal** shows your latest blog posts.
- **Customer support** lists how to reach you:
  - Each **Contact option** block opens a WhatsApp chat, a phone call, an email or a link.
  - WhatsApp uses the number in the block, or **Theme settings → WhatsApp** when the block is empty.
  - Add **Opening hours** and a button.
- The **Newsletter** signup saves subscribers in **Customers** with the `newsletter` tag.

## 8. Product cards

**Theme settings → Product cards → Card layout → Catalogue plate** (the default) shows:

- the photo;
- an italic caption with the plate number (its place in the list) and, with **Add the product type to the plate caption**, the type;
- the name and price on one line.

Quick add, quick view, size buttons, color swatches and saved items all work on it.

## 9. Product page

The product template has seven sections.

### 1. Product catalogue page

- **Plates**:
  - The product's photos are numbered plates. **Photos**: one under another, or the first large and the rest in pairs.
  - With **Show plate captions**, each plate reads Plate 01 followed by the photo's alt text, for example Front or Worn open. Set alt text in the product's media.
  - Tapping a photo opens it full screen.
  - When a shopper picks a color, the page moves to that variant's photo.
- **Beside the plates**, in place as shoppers scroll:
  - the collection, the name, the price and the star rating;
  - the buying blocks:
    - options and the **Size guide**;
    - stock status and the buy buttons;
    - the **Upsell** ("Pairs with") and the back in stock alert;
    - save, the **Delivery timeline**, payment icons and WhatsApp;
  - the description, then the **Details** accordion rows (details, fabric and care, fit, delivery and exchanges).
- **Phones**: the plates swipe with a counter, and the details follow below.

### 2–7. The other sections

**Wear it with** (frequently bought together), **Reviews**, **Worn by you** (videos), **You may also like**, **Recently viewed** and, at the end, **Questions and answers**.

### Size guide

The **Size guide** block opens a drawer with your size table. Write the table as text, one row per line with cells separated by `|`, or pick a page that has your size chart. Replace the example measurements with your real ones before you publish.

### Upsell

The **Upsell** block suggests other products under the buy buttons.

- **Style**:
  - checkboxes, where ticked items are added to the cart with the product;
  - small cards, each with its own add button;
  - a compact list.
- **Products**:
  - related, chosen automatically;
  - complementary, set in the Search & Discovery app;
  - products you pick.

### Delivery timeline

The **Delivery timeline** block shows three steps: ordered today, the ship date and the delivery dates.

- Set these to your real times:
  - **Days to prepare the order**;
  - the fastest and slowest delivery after shipping;
  - the cutoff hour;
  - the days you don't deliver.
- Before the cutoff it shows the time left to order.

## 10. Cart

- **Theme settings → Cart**: after adding to the cart, open the drawer, the cart page or checkout.
- **Free shipping bar**: turn on **Show a free shipping bar in the cart** and enter **Free shipping from** in your store currency. The bar shows in the cart drawer and on the cart page. It's only a message: set the real rate in **Settings → Shipping and delivery**.
- **Cart upsells**:
  - The cart drawer suggests products under the items. Set this in **Customize → Cart drawer**.
  - The cart page suggests them under the cart. Set this in **Theme settings → Cart → Cart page**.

## 11. Collection page

**Main collection** shows the collection name, description and catalogue plates with filters. Set up filters with the **Search & Discovery** app.

## 12. Footer

The **Margin footer** is set like a book's colophon:

- **Name** and a short italic **Note** sit on one side.
- Your blocks (email signup, menus, text) sit beside them, in 2 to 4 columns.
- The bottom line holds:
  - the copyright and policy links;
  - the **language selector** (with **Also show country and currency**);
  - social links;
  - payment icons.

Signups are saved in **Customers** with the `newsletter` tag. The popup and the mobile tab bar are in the footer group, turned off.

## 13. Before you add photos

**Theme settings → Layout → Frames without a photo → Clothing drawings** shows a flat drawing (tee, hoodie, pants, cap, sneaker, tote or jacket) until you add photos. When a product or collection name says what it is, in English or Arabic, the drawing matches it. **Drawing color 1–4** set the four colors of the drawings.

## 14. WhatsApp, Arabic and EGP

- **Theme settings → WhatsApp**: turn on the floating button and enter your number with the country code, digits only (for example `201001234567`).
- Add Arabic in **Settings → Languages**. The theme switches to right-to-left automatically, and the side rail moves to the right. Translate products with **Translate & Adapt**.
- The currency format comes from **Settings → General → Store currency**. **Theme settings → Language and currency** can hide `.00`.

## 15. Store setup checklist

- **Menus**: `main-menu` (the header and the footer's first menu) and `footer`. Give menu items sub-links for the menu panels.
- **Collections**: one per category (for example Shirts, Trousers, Knitwear, Outerwear). Add each to a Chapter block.
- **Photo alt text**: write short alt text on each product photo (Front, Back, Worn open). It becomes the plate caption.
- **Search & Discovery**: for filters and complementary products. Complementary products feed the upsells.
- **Shipping**: set rates in **Settings → Shipping and delivery**, then match the delivery timeline and the free shipping bar to them.
- **Reviews**: install a reviews app. The stars read the `reviews.rating` metafield.

## 16. Pages to create

| Page | Template |
| --- | --- |
| About | `about`: your page content, a statement, story rows, letters and customer support |
| Contact | `contact` |
| Reviews | `reviews` |
| Shipping | `shipping`: the delivery areas with time and fee |

## 17. Speed and accessibility

- Fonts are bundled and only the ones in use load. Images are sized responsively and lazy loaded.
- Effects only run while on screen. Visitors who turn on reduced motion see everything in place.
- The side rail, its panels, search, drawers, the plates and the accordion rows work with the keyboard and screen readers.
