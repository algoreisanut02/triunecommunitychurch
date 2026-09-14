# Triune Community Church — HTML site

Plain HTML, CSS, and a little JavaScript. No Node, no WordPress, no build step.

## Put it online

**GitHub Pages**
1. Create a repository.
2. Upload every file in this folder to the root (so `index.html` is at the top).
3. Settings → Pages → Deploy from branch `main` / root.
4. Site will be at `https://YOURUSER.github.io/REPO/`.
5. Then add www.triunecommunitychurch.com as a custom domain.

**Cloudflare Pages**
1. Upload this folder, or connect the GitHub repo.
2. Build command: leave empty. Output directory: `/` (or leave default).
3. Add custom domains. Free SSL.

**OnlyDomains / any cPanel host**
Upload this folder to `public_html`. `index.html` is the home page.

Do not change MX records. Email stays info@triunecommunitychurch.com.

## Edit later

- Copy and address: the `.html` files
- Colors: `css/site.css`
- Photos: `images/`
- Forms currently only show a thank-you. To email the church, a volunteer can point them at Formspree or similar.
