# Thai Trung Kien — Data Analytics Engineer Portfolio

Static portfolio site: home page + 7 project case studies. No build step — plain HTML/JS.

## Structure
- `index.html` — home page (copy of `Portfolio Home.dc.html`)
- `Case Study *.dc.html` — 7 case study pages
- `support.js` — page runtime (required, same folder)
- `image-slot.js` — drag-and-drop image placeholders
- `assets/` — images, logos, generated previews

## Deploy on GitHub Pages
1. Create a repo (e.g. `portfolio`) and push this folder's contents to the root.
2. Settings → Pages → Deploy from branch → `main` / root.
3. Site serves at `https://<user>.github.io/portfolio/`.

## Custom domain
Add a `CNAME` file containing your domain, point DNS (CNAME → `<user>.github.io`), then set the domain in Settings → Pages.

## Notes
- Image slots (avatar, screenshots): replace by editing the `src="assets/..."` attribute or dropping files into `assets/` with the same names.
- The Green SM card embeds the live dashboard via iframe; it requires network access when viewing.
