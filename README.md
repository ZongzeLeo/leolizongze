# Zongze (Leo) Li — Personal Website

Minimalist personal academic website. Four files, zero dependencies, instant GitHub Pages deploy.

## File Structure

```
index.html          ← Home: hero, research areas, publications summary
publications.html   ← Full publications (published / under review / in prep)
background.html     ← Education + Research Experience + Awards
shared.css          ← All shared styles, dark mode, nav, layout
```

## Deploy to GitHub Pages

1. Create a repo named **`<your-username>.github.io`**
2. Upload all four files to the root
3. **Settings → Pages → Source: main branch / (root)**
4. Live at `https://<your-username>.github.io`

## Adding Your Photo

In `index.html`, find the `.photo-placeholder` div and replace it:

```html
<!-- Before -->
<div class="photo-placeholder">...</div>

<!-- After -->
<img src="photo.jpg" alt="Zongze Li" />
```

Upload `photo.jpg` to the same folder. Recommended: 600×800px, portrait orientation.

## Adding Lab Photos

In `background.html`, each experience block has a `.lab-photo-placeholder` div. Replace with:

```html
<!-- Before -->
<div class="lab-photo-placeholder">...</div>

<!-- After -->
<img src="images/rcl-lab.jpg" alt="Robotics and Control Lab, UBC" />
```

Create an `images/` folder and add:
- `images/rcl-lab.jpg`       ← UBC Robotics and Control Lab
- `images/softbio-lab.jpg`   ← CityU Soft Bio-electronics Lab
- `images/robotics-lab.jpg`  ← CityU Biomedical Robotics Lab
- `images/sunlab.jpg`        ← CityU Dong Sun's Lab

Recommended: 1200×440px, landscape, well-lit lab/equipment shots.

## Customise

| What | Where |
|------|-------|
| Email address | `index.html` — contact section |
| LinkedIn URL  | `index.html` — contact section |
| GitHub URL    | `index.html` — contact section |
| Google Scholar link | `index.html` — hero buttons |
| Publications (under review / in prep) | `publications.html` |
| Co-authors on in-prep paper | `publications.html` — "co-authors TBD" |
