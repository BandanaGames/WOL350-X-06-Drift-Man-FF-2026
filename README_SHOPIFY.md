Shopify Theme conversion — minimal scaffold

What I added
- `layout/theme.liquid` — theme layout that loads `style.css` and `main.js` from `assets/`
- `templates/index.liquid` — homepage composed from sections
- `sections/*` — `hero`, `products`, `lookbook`, `gallery`, `music`, `exclusive`, `footer`
- `assets/style.css` and `assets/main.js` — CSS/JS copied from the original site
- `config/settings_schema.json` — minimal theme settings

Next steps to deploy and test locally
1. Install Shopify CLI: https://shopify.dev/docs/cli
2. From theme folder run:

```bash
shopify theme serve
```

3. Use the theme editor to assign the `Products` section a collection so product loops display actual products.
4. Upload images/audio/video to the theme `assets/` or use Shopify Files and update references.

Want me to:
- wire up collection handles and sample product data, or
- prepare a zip of the theme ready to upload to Shopify?
