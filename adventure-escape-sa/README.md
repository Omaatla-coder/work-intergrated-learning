# Adventure Escape SA — Website

A complete multi-page static website for **Adventure Escape SA**, an outdoor adventure company based in the Western Cape, South Africa.

## Design system (from the provided wireframe)

| Token        | Value     | Use                          |
|--------------|-----------|------------------------------|
| Cream        | `#FFF8E1` | Page background              |
| Navy         | `#0A2540` | Header, footer, dark buttons |
| Orange       | `#FF6F00` | Primary CTAs, active nav     |
| Green        | `#2E7D32` | Accent text, prices          |
| Mid green    | `#7EA88A` | Landscape hills              |
| Light green  | `#DCE9DF` | Card image backgrounds       |
| Sun          | `#F9C66B` | Decorative sun               |
| Slate        | `#64748B` | Body / secondary text        |
| Font         | Inter     | All text                     |

## Pages

| File            | Description                                      |
|-----------------|--------------------------------------------------|
| `index.html`    | Home — hero + featured activities                |
| `about.html`    | About the company, values, operating area        |
| `packages.html` | Single, Cape Explorer & Weekend Escape packages  |
| `activities.html` | Detailed activity cards (zipline, kayak, climb) |
| `fees.html`     | Pricing, inclusions, discounts & policies        |
| `contact.html`  | Contact details + booking enquiry form           |

## How to view

Open any HTML file in a browser, or serve the folder locally:

```bash
cd adventure-escape-sa
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

All pages share the same header navigation and footer so the site feels connected as one product.
