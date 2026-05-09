# My Research Website

A minimalistic academic personal website built with plain HTML/CSS, designed for GitHub Pages hosting.

## Features

- Single-file HTML — no build step, no dependencies beyond Google Fonts
- Sections: Bio · Publications · Teaching · Projects · Contact
- Botanical/bird illustrations as SVG background decorations
- Fully responsive (mobile-friendly)
- Smooth scroll navigation with active link highlighting

## How to Deploy to GitHub Pages

1. Create a new GitHub repository named **`yourusername.github.io`** (replace with your actual GitHub username).
2. Upload `index.html` to the root of that repository.
3. Go to **Settings → Pages**, set Source to `main` branch / root.
4. Your site will be live at `https://yourusername.github.io` within a few minutes.

## Customisation Checklist

Open `index.html` and replace every placeholder:

| Placeholder | Replace with |
|---|---|
| `Dr. [Your Name]` / `YourName` | Your actual name |
| `[Your Institution]` | Your university or lab |
| `[Department Name]` | Your department |
| `[City, Country]` | Your location |
| Publication entries | Your real papers (title, authors, journal, DOI) |
| Course entries | Your actual courses |
| Project entries | Your real projects & funders |
| All `href="#"` / social links | Your real URLs |
| `you@university.edu` | Your email address |
| Office address block | Your office address |

### Adding Your Photo

Find the `<div class="bio-portrait">` block and replace its contents with:

```html
<img src="photo.jpg" alt="Your Name" style="width:100%;height:100%;object-fit:cover;">
```

Then upload `photo.jpg` alongside `index.html`.

### Colours

All colours are CSS variables at the top of the `<style>` block:

```css
--ink:   #1a1a18   /* main text */
--paper: #f5f2eb   /* background */
--sage:  #7a8c6e   /* green accent */
--mist:  #b8c4b0   /* subtle borders */
--warm:  #c8a97a   /* warm gold accent */
```

Adjust them to match your taste.
