# Developer Portfolio (Static)

Simple static portfolio scaffold with 5 pages and Tailwind CDN.

Pages:

- index.html (home)
- about.html
- projects.html
- blog.html
- contact.html (contact form uses Formspree)

Note: This site has been converted to a single long-scroll page. Use `index.html` as the canonical entrypoint — navigation links are anchors (`#about`, `#projects`, `#blog`, `#contact`). The other HTML files remain for reference but the single-page `index.html` is the main site.

Quick preview:

```bash
# from the project root
open index.html
# or serve with a simple HTTP server
python3 -m http.server 8000
# then browse http://localhost:8000
```

Notes:

- Replace `you@example.com` and the Formspree action with your real contact info.
- Add `assets/resume.pdf` if you want a downloadable resume.
