# ARVIBA NATURALS — static storefront

Plain HTML, CSS, Bootstrap 5 and vanilla JavaScript. No build step, no PHP.

## Folder structure

```text
index.html        Home
shop.html         Product listing (search, category, sort)
product.html      Product detail (?id=multani-mitti)
cart.html         Cart (saved in the browser, survives refresh)
checkout.html     Delivery form + order summary
about.html        Brand story
contact.html      Contact form + FAQ
assets/css/       style.css
assets/js/        config.js, products.js, cart.js, main.js, app.js
assets/images/    Product photos (replace with your own, same file names)
```

## What to edit

- `assets/js/config.js` — brand name, WhatsApp number, phone, email, address,
  social links, delivery charge and free-delivery threshold.
- `assets/js/products.js` — products: name, price in PKR, size, benefits,
  usage steps, ingredients, image path.
- `assets/images/` — drop in your own square photos using the same file names.

## Publish on GitHub Pages

1. Copy the contents of this folder into the root of a GitHub repository.
2. Repository → Settings → Pages → Source: `Deploy from a branch`,
   branch `main`, folder `/ (root)`.
3. The site goes live at `https://<username>.github.io/<repo>/`.
