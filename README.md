# SmartShop – Scan & Go Prototype

A self-scan prototype built with vanilla HTML/CSS/JS.

## Features

-  Live barcode scanning via camera (Quagga.js)
-  Manual barcode entry
-  Real product data from Open Food Facts API (no key required)
-  6 bundled example products (works offline)
-  Payment sheet with Apple Pay / Google Pay (OS-detected) + card scan UI
-  Mobile-first responsive design

## Usage

Just open `smartshop.html` in a browser — no build step, no server needed.

```bash
git clone https://github.com/karthic180/smartshop.git
cd smartshop
open smartshop.html
```

## Tech Stack

| Thing | License |
|-------|---------|
| [Quagga.js](https://github.com/ericblade/quagga2) | MIT |
| [Open Food Facts API](https://world.openfoodfacts.org) | ODbL |
| [Nunito Font](https://fonts.google.com/specimen/Nunito) | OFL |
| [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) | OFL |

## Attribution

Product data provided by [Open Food Facts](https://world.openfoodfacts.org) — a free, open, collaborative database of food products from around the world.

## License

MIT — see [LICENSE](LICENSE)
