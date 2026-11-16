# Odoo-Education-Program-Bangladesh

A single-page marketing website for the "Odoo Education Program Bangladesh", a university course programme facilitated by Metamorphosis Ltd.

## What it does

`index.html` is a static landing page. It presents the programme (24 months of free Odoo Enterprise licences, cloud hosting and faculty training for Bangladeshi universities) and has these sections: curriculum, industries, and "Class to Career". It also has a university sign-up form.

The sign-up form is front-end only. Submitting it shows an alert and sends no data anywhere. The figures shown on the page (such as installations and local jobs) are page content, not read from any data source.

## Tech stack

- Plain HTML and JavaScript in one file
- Tailwind CSS via the CDN script
- Font Awesome and Google Fonts (Inter, Outfit) via CDN

## Folder layout

```
index.html        the whole site
CONTRIBUTING.md   contribution steps
.gitignore
```

## Run

There is no build step or package manifest. Open `index.html` in a browser, or serve the folder with any static file server. An internet connection is needed for the CDN assets.

## Environment variables

None.

## Status

A static page with no tests and no backend.
