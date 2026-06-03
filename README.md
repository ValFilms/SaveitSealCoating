# Save It Sealcoating — Website

A simple, fast, mobile-friendly website for Save It Sealcoating.
Crack Repair · Paving · Sealcoating · Pot Hole Repair — Commercial & Residential, Burlington County, NJ.

**Phone:** (856) 883-5788

## Files

| File | Purpose |
|------|---------|
| `index.html` | Home page |
| `services.html` | Services detail page |
| `about.html` | About page |
| `contact.html` | Contact page (tap-to-call + map) |
| `styles.css` | All styling (shared by every page) |
| `favicon.svg` | Browser tab icon |

It's a plain static website — no build step, no dependencies to install.

## How to deploy on GitHub Pages (free)

1. Create a new repository on GitHub (e.g. `save-it-sealcoating`).
2. Upload **all of these files** to the repository (drag-and-drop works:
   on the repo page click **Add file → Upload files**, drop everything in, then **Commit changes**).
   Make sure `index.html` sits in the **root** of the repo, not inside a sub-folder.
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Set **Branch** to `main` and folder to `/ (root)`, then **Save**.
6. Wait ~1 minute. GitHub shows the live URL at the top of the Pages settings,
   usually `https://<your-username>.github.io/save-it-sealcoating/`.

That URL is your live site. Every time you upload changed files, it updates automatically.

### Using a custom domain (optional)
In **Settings → Pages → Custom domain**, enter your domain (e.g. `saveitsealcoating.com`)
and follow GitHub's instructions to point your domain's DNS at GitHub Pages.

## Editing later

- **Phone number:** it appears as `tel:+18568835788` links and as the displayed
  `(856) 883-5788` text. Search/replace both if the number ever changes.
- **Photos:** the work photos are free stock images loaded from Pexels. To use real
  job photos, add image files to the repo and replace the `https://images.pexels.com/...`
  `src` values in the HTML with your file names (e.g. `src="my-driveway.jpg"`).
- **Hours:** edit the hours list in `contact.html`.
- **Service area / towns:** edit the lists in `index.html` and `contact.html`.

## Notes
- Works on phones, tablets and desktops.
- The map is a free Google Maps embed (no API key needed).
