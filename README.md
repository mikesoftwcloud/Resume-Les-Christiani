# Leslie Christiani — Portfolio Site

## Deploy to GitHub Pages
1. Create a new repo on GitHub (e.g. `leslie-portfolio`).
2. Upload `index.html` and the `assets/` folder (keep the folder structure — don't flatten it).
3. Go to the repo's **Settings → Pages**.
4. Under "Build and deployment," set Source to **Deploy from a branch**, branch `main`, folder `/ (root)`. Save.
5. Your site goes live at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

## Adding the intro video later
Drop your video file (e.g. `intro.mp4`) into the `assets/` folder, then add this where you want it in `index.html`, inside the hero or a new section:

```html
<video controls poster="assets/leslie.png" style="width:100%; max-width:600px;">
  <source src="assets/intro.mp4" type="video/mp4">
</video>
```

Or, if you upload it to YouTube/Vimeo instead, swap in an `<iframe>` embed from there.
