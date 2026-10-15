# Fashion Marketplace

HTML & CSS homework: multi-page Fashion Marketplace website (Figma community design).

**Technologies:** HTML5, CSS3 (Flexbox, Grid, CSS variables). No JavaScript, no frameworks.
**Fonts:** Poppins, Inter (Google Fonts).
**Design:** https://www.figma.com/design/eRIbFYL9ZJBluxw5Z8WV3t/Fashion-Marketplace--Community-

## Pages
| File | Page |
|---|---|
| `index.html` | Home |
| `explore.html` | Explore Collections |
| `fashion-shows.html`, `fashion-show.html`, `watching.html` | Fashion Shows, single show, full screen |
| `all-nft.html` | Personal Collection (filters + items) |
| `brand-store.html` | Product / brand store page |
| `drops.html`, `brand-page.html` | Drops, Brand page |
| `market.html`, `stats.html` | Market stats, Top market statistics |
| `community.html`, `messages.html` | Feeds, Messages |
| `creator-studio.html`, `creators-market.html` | Creator Studio, Creators Market |
| `edit-profile.html`, `model-3d.html` | Profile, 3D Meta Look |
| `about.html` | About Us |
| `sign-in.html`, `sign-up.html` | Auth |

**Structure:** `assets/css/reset.css`, `style.css` (home + shared), `pages.css` (inner pages), `assets/images/`.
**Run:** open `index.html` in a browser; the header menu links all pages together.

**Notes:** semantic HTML (`header`, `nav`, `main`, `section`, `article`, `footer`), reusable `.product-card` / `.product-grid`, CSS variables in `:root`, shared `.container`, Flexbox + Grid, hover/transition on buttons, responsive breakpoints at 1100px / 700px. All icons are inline SVG.
