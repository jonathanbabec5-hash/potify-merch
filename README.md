# POTIFY Merch Directory

[Complete repository directory tree](docs/DIRECTORY.md)

**Store integration reference.** Connect the book, film and games to a real merchandise destination.

### Setup and usage

Use Node.js 24 for the included checks. Use Python 3 for the local static preview.

```sh
python3 -m http.server 8000 --bind 127.0.0.1 --directory public
```

Visit the official storefront. Open http://127.0.0.1:8000/ in a browser. 

### Developer entry points

A small public catalog records the established store and product link from the First Cycle edition. Checkout and fulfillment belong to the merchant platform. Explore `public/`, `src/`, `tests/` in the full tree.

### Verification

The public entry page returned HTTP 200 and rendered local content in Chromium at a 390 × 844 viewport.

```sh
node --test tests/project.test.mjs
```

### Release scope

Product stock, pricing, order export and current conversion are unknown. The reference never processes payment. potify-first-cycle at `7bc29685d6decd1f3d1bbbb0216f837bc7701a51`. Exact official store and tote destinations from the published book view. New integration reference; no order data or live catalog synchronization.

[Technical whitepaper](docs/WHITEPAPER.md) · [Marketing and sales plan](docs/MARKETING.md) · [Dated developer log](docs/BUILD-LOG.md)

Existing asset and code terms remain applicable. Public access to a recording, illustration, brand or manuscript does not itself grant commercial reuse rights.
