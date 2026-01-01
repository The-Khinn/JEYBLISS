[README.md](https://github.com/user-attachments/files/24402468/README.md)
# JEYBLISS Enterprise Website

A professional, responsive static website for JEYBLISS Enterprise.

## Structure
- `index.html` — Home
- `about.html` — Company info
- `services.html` — Offerings
- `compliance.html` — GIFMIS & compliance details
- `contact.html` — Contacts & quote form (demo)
- `privacy.html`, `terms.html` — Legal pages
- `css/styles.css` — Styles
- `assets/favicon.svg` — Favicon/logo

## How to preview locally
Open `index.html` in your browser. For best results, run a simple local server:

```bash
python3 -m http.server 8080
# then visit http://localhost:8080/jeybliss-website/index.html
```

## How to deploy (free options)
### Netlify
1. Create a Netlify account.
2. Drag-and-drop the `jeybliss-website` folder onto Netlify.
3. Set a custom domain (e.g., `jeybliss.com`) or a Netlify subdomain.

### GitHub Pages
1. Create a new GitHub repository.
2. Push the contents of `jeybliss-website`.
3. Enable GitHub Pages (Settings → Pages → Deploy from `main` → `/` root).
4. Your site will be live at `https://<username>.github.io/<repo>/`.

### Custom domain
Update DNS `A` or `CNAME` records with your registrar to point to your hosting provider.

## Next steps
- Replace social links with real profiles.
- Connect the contact form to email or Netlify Forms.
- Add product/service catalog images.
- Upload certificates (registration & tax clearance) to `assets/` and link them from `compliance.html`.
