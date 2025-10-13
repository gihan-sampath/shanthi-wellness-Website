# Simple Static Site (Vercel-ready)

**What you get**
- Pure HTML/CSS/JS (no build step)
- Accessible, responsive, fast
- Vercel-ready (`vercel.json`) with long-term caching for assets
- `index.html`, `about.html`, `robots.txt`, `sitemap.xml`

## How to use
1. Replace `example.com` in `index.html`, `sitemap.xml`, and `robots.txt` with your domain (or leave it).
2. Drop your images into `/assets` and update the `<meta>` image if you want.
3. Push this folder to a GitHub repo.
4. On Vercel: **New Project → Import Git Repository** → Framework: _Other/Static HTML_ → Deploy.

## Local preview (optional)
Just open `index.html` in your browser, or run a tiny server:

```bash
python3 -m http.server 8080
# then visit http://localhost:8080
```
