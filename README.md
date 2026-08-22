# Hâpax Concrete Coatings — Site (v1 draft)

Single-file MVP site: `index.html`. No build step, no dependencies — just a static HTML file with inline CSS.

## What's still placeholder

1. **Brand colors / logo** — accent color is now `#97AB35` (the hâpax green), sampled from a screenshot of the logo, set as `--accent` in `index.html`. Close but not guaranteed exact — sample from the actual logo file for a precise match. The logo itself is still a text wordmark in the header/footer; swap in the real logo image (`assets/logo.png`) when you have the file.
2. **Quote form** — the form points to `https://formspree.io/f/YOUR_FORM_ID`, which doesn't work yet. To activate it:
   - Create a free account at [formspree.io](https://formspree.io) using hello@hapax.us
   - Create a new form, verify the email
   - Replace `YOUR_FORM_ID` in `index.html` (search for `formspree.io/f/`) with the real form ID
3. **Domain** — TBD per our conversation (`hapaxgarage.com` or similar). Once picked, register it and point it at GitHub Pages.
4. **Photos** — no real project photos yet since this is a new division. The site currently uses color swatches instead of photography. Add real before/after garage photos as they become available — that will do more for conversion than anything else on the page.

## Deploying to GitHub Pages

1. Create a new GitHub repo (e.g. `hapax-garage-site`).
2. Add this `index.html` (and an `assets/` folder for the logo/photos once you have them) to the repo root.
3. In the repo: Settings → Pages → Deploy from branch → `main` / root.
4. GitHub gives you a `https://<username>.github.io/<repo>/` URL immediately.
5. Once you register a real domain, add a `CNAME` file with the domain name, and point the domain's DNS at GitHub Pages (A records to GitHub's IPs, or a CNAME record if using a subdomain).

I can do all of this for you once you confirm the domain and I have write access to the GitHub repo.

## Structure of the page

Hero + quote form → Why Epoxy (vs. polyurea) → Services (coatings live, storage "coming soon") → Process → Materials (Torginol) → Service area → About/Contact → FAQ → CTA → Footer. Sticky call/quote bar on mobile.
