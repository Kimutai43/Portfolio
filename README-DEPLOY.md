# Brian Kimutai — Portfolio refresh

This is a static GitHub Pages portfolio. It uses plain HTML, CSS and JavaScript; no build step or package installation is required.

## Preview locally

Open `index.html` in a browser, or run a local static server from this folder:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000/Portfolio-main/` if serving from the parent folder, or `http://localhost:8000/` if serving inside this folder.

## Publish to GitHub Pages

1. Keep a backup of the current repository before replacing files.
2. Copy the refreshed site files into the root of the `Portfolio` repository.
3. Preserve `.nojekyll`, `.well-known/security.txt`, `robots.txt`, `sitemap.xml`, `profile.jpg`, and `bg.jpg`.
4. Confirm GitHub Pages is configured to deploy from the intended branch and root folder.
5. Commit and push the changes, then verify `https://kimutai43.github.io/Portfolio/` on desktop and mobile.

## Before publishing — review these items

- The old `Brian_Kimutai_Kochilinyang_CV.pdf` from the source ZIP was not copied into this refresh because its dates and experience details conflict with the updated portfolio information. Upload a current, verified CV separately before adding a downloadable CV link.
- Check the public contact details (email and phone) and LinkedIn URL.
- The Web3Forms access key was retained from the existing site. Submit a test message after deployment to confirm the form still works.
- Project cards that link to the GitHub profile rather than a specific repository should be updated with exact repository URLs when those repositories are public.
- Verify every certification title and issuer against the original credential before treating the list as a formal credential register.

## Files

- `index.html` — refreshed responsive portfolio
- `profile.jpg`, `bg.jpg` — existing images
- `.well-known/security.txt` — existing security contact policy
- `robots.txt`, `sitemap.xml`, `.nojekyll` — existing GitHub Pages/SEO files
