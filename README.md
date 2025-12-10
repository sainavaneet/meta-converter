# iPhone 15 Pro Max EXIF Embedder (Client-side)

This is a **single-page** website that lets you upload a JPEG and embed these EXIF fields:
- `Make`: Apple
- `Model`: iPhone 15 Pro Max
- `LensModel`: Main Camera (24 mm, f/1.78, 48 MP)

Everything runs **in your browser** using [piexifjs]. No server needed.
The edited image is immediately downloaded

## How to use
1. Open `index.html` in any browser.
2. Pick a JPEG file.
3. Click **Embed EXIF & Download**.
4. Check Info/Details on iPhone—camera should show *iPhone 15 Pro Max*.

## Deploy options
- **Local**: Just double‑click `index.html`.
- **GitHub Pages**: Create a repo, add this file, enable Pages on `main` → `/ (root)`.
- **Any static host**: Netlify, Vercel, Cloudflare Pages, etc.

## Notes
- Works offline after the first load (the page references `piexifjs` from a CDN; for fully-offline use, download the library and serve it locally).
- Only JPEG is supported for EXI
