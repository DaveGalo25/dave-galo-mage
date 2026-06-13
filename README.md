# David Galotto Image Gallery

Static, crawlable photo gallery for David Galotto.

## Files

- `index.html` contains the public gallery, semantic image markup, Open Graph metadata, and Person/ImageObject structured data.
- `photos/*.html` contains one dedicated landing page per image.
- `assets/images/*.png` contains the public photos with descriptive filenames.
- `robots.txt` allows crawling and points bots to `sitemap.xml`.
- `sitemap.xml` lists every page and image using Google's image sitemap namespace.

## Deployment

Host the folder as a static site. If the production domain is not `https://david-galotto.vercel.app`, replace that URL in:

- `index.html`
- `photos/*.html`
- `robots.txt`
- `sitemap.xml`

After deployment, submit `https://your-domain.com/sitemap.xml` in Google Search Console.
