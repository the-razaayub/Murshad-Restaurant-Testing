# Murshad Restaurant and Pizza Crust — Website

Responsive restaurant website built from the supplied logo and menu.

## Main pages
- index.html — home, auto slider, featured menu, service options
- fast-food.html — complete fast-food menu grouped by category
- desi-items.html — complete desi menu grouped by category

## Replaceable images
- assets/murshad-logo-transparent.png — transparent logo
- assets/slider-1.jpg ... slider-5.jpg — 5 promotional hero slider banners (ratio 2.46:1, 1600×650px, JPG) with key food and titles composed inside the mobile-safe center zone.
- assets/menu/ — 114 unique, web-optimized 900×900px (1:1 square) food photographs, one per menu item, named after each dish in lowercase with hyphens.
- assets/story-food.jpg — "Our Story" section image on the home page (1180×1000px, JPG).

## Keeping the site fast
- Menu photos: square, about 900×900px, compressed JPG or WebP, ideally under 100 KB each.
- Slider images: 1600×650px, ideally under 250 KB each.
- Story image: 1180×1000px, ideally under 200 KB.
- Free tools like squoosh.app or tinypng.com shrink photos without visible quality loss.
- A loading screen (logo and moving bar) appears only if a page takes longer than
  about half a second to load.

## Ordering
This website works two ways, side by side:

1. **WhatsApp ordering** — live out of the box, no setup needed. Opens a
   pre-filled WhatsApp message with the order details.
2. **Website ordering** (the "Submit Website Order" button) — saves the
   order to a real database and shows it in the admin panel, once the
   backend is connected.

Until the backend is connected, the "Submit Website Order" button will show
a message asking the customer to use WhatsApp instead, rather than silently
failing or pretending the order went through.

**See `SETUP INSTRUCTIONS.docx`** (in the top level of this delivery, next
to the `website` and `backend` folders) for plain, step-by-step instructions
to connect the backend, publish everything, and create your admin login.

## The admin panel and backend
These now live in the separate `backend` folder of this delivery, not inside
this website folder. The backend is a real server with a database — it is
not a demo. See `SETUP INSTRUCTIONS.docx` for how to deploy it and open your
admin panel.
