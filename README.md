# Mariella Buque — Portfolio (PWA)

Static, installable portfolio site. No build step.

## Deploy on GitHub Pages
1. Create a repo and push these files to the root of the `main` branch.
2. Settings → Pages → Deploy from a branch → `main` / `(root)`.
3. Visit `https://<username>.github.io/<repo>/`.

## Edit your content
- Open `index.html` and search for `[` to find every placeholder (bio, email, links, projects, experience, education, testimonials).
- Projects, skills, jobs and testimonials are arrays near the bottom of the file.
- Contact form: set `ENDPOINT` in the script to a Formspree/Netlify/your own URL.
- Set the real `og:image` URL (use a 1200×630 image).

## PWA notes
- `manifest.webmanifest` and `sw.js` use relative paths, so it works on project sites (`/repo/`).
- After changing files, bump `V` in `sw.js` (e.g. `mb-portfolio-v2`) so visitors get the update.
- Icons live in `icons/`. Replace them with your own if you like.
