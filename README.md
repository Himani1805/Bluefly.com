# Bluefly

A static designer-fashion storefront. The page is one HTML file and one stylesheet, with every photo saved in the project so the layout still works offline.

## About

Bluefly is a shopping page for luxury fashion at discounted prices. It brings clothing, shoes, handbags, sunglasses, jewelry, and accessories onto one screen, with sale banners, a category grid, recommended products, new arrivals, and a clearance row.

There is no cart, checkout, or account backend. Search, the bag icon, and the nav links stay on this page and scroll to the matching section. Orders shown on the welcome bar include free standard shipping and handling over $199.

## What you will see

- A white header with the logo, search, account, wishlist, and bag
- Promo banners for designers, handbags, and shoes
- Recommended products and new arrivals
- Shop by category, including dresses, heels, handbags, sunglasses, and jewelry
- Three equal sale cards for denim, jumpsuits, and accessories
- A footer with help links and an email signup

## Open it

Any static file server works. From this folder:

```bash
npx --yes serve -l 5000 .
```

Then open [http://localhost:5500/](http://localhost:5000).

You can also open `index.html` directly in a browser. The Google font links need a network connection. The pictures do not.

## Project layout

```text
index.html    page structure and the two banner sliders
style.css     layout, including the phone and tablet sizes
images/       logo, icons, banners, products, and category photos
```
