# Cleaning Geniee — website prototype

A single self-contained page (`index.html`) — no build step, no dependencies to install.

## Publish with GitHub Pages

1. Create a new GitHub repository (e.g. `cleaning-geniee-site`).
2. Add `index.html` to the repo root and commit/push it.
3. In the repo: **Settings → Pages → Source**, choose the `main` branch and `/ (root)` folder, then **Save**.
4. GitHub gives you a live URL shortly after, usually:
   `https://<your-github-username>.github.io/<repo-name>/`
5. To use `cleaninggeniee.com` instead: add a `CNAME` file to the repo root containing just the domain
   (`cleaninggeniee.com`), and point your domain's DNS at GitHub Pages (an `A` record to GitHub's IPs,
   or a `CNAME` record to `<username>.github.io` if using a subdomain). GitHub's own Pages docs walk
   through the exact DNS records to add.

## Notes before going live

- The contact form shows a confirmation message but doesn't send anywhere yet — it needs a backend or a
  form service (e.g. Formspree, Google Forms) wired into the `fetch`/`submit` handler in `index.html`.
- Social links point to `instagram.com/cleaninggeniee` and `facebook.com/cleaninggeniee` — confirm these
  match the real page URLs.
- Phone: +91 98856 91 666 · WhatsApp: +91 98856 92 666 · Email: cleaninggeniee.co@gmail.com
