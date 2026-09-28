# LUMINA Perfume Store

A front-end e-commerce course project prepared for the Web Design course. The site is intentionally built with local libraries and a clear folder structure so it can be demonstrated offline except for Ajax, which needs a local HTTP server (such as VS Code Live Server) or GitHub Pages.

## Project structure

- `html/` — website pages
- `css/` — Bootstrap and custom responsive styling
- `js/` — jQuery, Bootstrap bundle, and project JavaScript
- `images/` — product images and favicon
- `videos/` — reserved media folder
- `fonts/` — local Font Awesome and Roboto files
- `engine1/` + `data1/` — WOWSlider files
- `vendor/toastify/` — Toastify 1.12.0 notification library (MIT)
- `ajax/` — two separate HTML fragments loaded into Bootstrap modals with jQuery Ajax

## Course requirements checklist

- Separate project folders: HTML, CSS, JS, images, videos, fonts, Ajax, libraries.
- Semantic HTML layout: `header`, `nav`, `main`, `section`, `aside`, `footer`.
- Headings, paragraphs, lists and a table are used.
- Eight website pages are included: Home, Shop, About, Contact, Sign In, Register, Cart, Product Detail.
- Contact page uses local Font Awesome icons.
- Register and Sign In forms use HTML5 + JavaScript validation.
- Home page uses WOWSlider.
- Product layout uses Bootstrap Grid; custom Flexbox is also used.
- `css/styles.css` includes multiple responsive Media Queries.
- Toastify notifications appear for add-to-cart, forms, and demo actions.
- Two Bootstrap Modals are loaded by jQuery `$.ajax()` from `ajax/offer-modal.html` and `ajax/shipping-modal.html`.
- Bootstrap is local.
- jQuery is local.
- Root `index.html` is included so the project works on GitHub Pages.

## Run locally

For the full project, open the root folder with **VS Code Live Server** and visit `index.html`. Do not open the file directly with `file://` when demonstrating Ajax because browsers normally block local Ajax requests.

## GitHub Pages

Upload the whole project to a GitHub repository. Then open **Settings → Pages**, choose **Deploy from a branch**, select the main branch and `/ (root)`, and save. The root `index.html` redirects to `html/index.html`.
