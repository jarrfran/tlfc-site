# tlfc-site

Hosted code for The League for Clubs website (Squarespace).

- `tlfc.js`: every page's code. A Squarespace Code Block holds only `<div data-tlfc="NAME"></div>` and this file fills it in.
- `site.css`: site-wide styles (header button, dropdown menus, mobile notch colour).
- `header-injection.html`: what goes in Squarespace → Settings → Developer Tools → Code Injection → Header (once).
- `index.html`: list of page names.

The files are generated; update them by replacing them with a new build. Pages pick up changes within a few minutes.
