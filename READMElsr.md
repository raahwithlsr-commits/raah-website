# RAAH LSR – Campus Navigator

Open `index.html` in a browser, or host free with GitHub Pages (Settings → Pages → Deploy from branch → main / root).

- `index.html` – page shell (header, nav, splash animation)
- `css/style.css` – all styling (the two polished pages are at the very bottom)
- `js/app.js` – all pages, room data, menus (edit prices in `const M`), gallery (`const GAL`), contacts
- `images/` – every photo/map; image names are listed in `const IMG` at the top of `app.js`

To add a gallery photo: put it in `images/`, then add `{t:'Caption',c:'Category',s:'images/yourfile.jpg'}` to `GAL` in `js/app.js`.
