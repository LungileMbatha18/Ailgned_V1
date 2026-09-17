# AILGNED — Coming Soon Website

Plain HTML5 + CSS3 only.

## Image placeholders

Replace these placeholder references with your real AILGNED imagery:

- `assets/images/hero.jpg`
- `assets/images/collection-01.jpg`
- `assets/images/collection-02.jpg`
- `assets/images/collection-03.jpg`
- `assets/images/collection-04.jpg`
- `assets/images/performance.jpg`
- `assets/images/journal-01.jpg`
- `assets/images/journal-02.jpg`
- `assets/images/journal-03.jpg`

The current design intentionally uses visible editorial placeholders so the layout can be developed before the final photography is uploaded.

## How to add an image

For example, change:

```html
<div class="image-placeholder">
  <span>HERO CAMPAIGN IMAGE</span>
  <small>assets/images/hero.jpg</small>
</div>
```

to:

```html
<img src="assets/images/hero.jpg" alt="Black South African model wearing AILGNED in a brutalist architectural space">
```

Then apply the existing image styling if necessary.

## Local preview

Open `index.html` directly in a browser, or use VS Code Live Server.

## Important

The waitlist form is visual only until you connect it to a backend/email service. No unnecessary JavaScript has been included.


## Supplied imagery
The supplied AILGNED hero, campaign, and product WebP images are wired into the page under `assets/images/hero`, `assets/images/campaign`, and `assets/images/products`.
