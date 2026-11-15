# BCRP website — frontend template
Static HTML/CSS/JS. Edit `build.py` (layout/components) and `content.py` (page text), then run `python3 build.py` to regenerate every page.

- `index.html`, `404.html` — root pages; all others in `/pages`
- `css/style.css` — design system (palette tokens at the top, sampled from the logo)
- `js/main.js` — loader, curtain transitions, slider, scroll reveal, tilt, greeting, toasts
- Backend hooks (events on `window`): `bcrp:login` {role,id,pw} and `bcrp:form` {form fields}
- Icons use Font Awesome and fonts use Google Fonts via CDN (internet needed)
