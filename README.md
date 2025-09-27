# mechmadhog-cdn

Personal CDN for MechMadHog projects.  
This repository hosts shared assets (**CSS**, **JS**, **images**, **fonts**, and **media**) delivered through [jsDelivr](https://www.jsdelivr.com/) for use in CodePen demos, FCC projects, and websites.

---

## 📑 Asset index

### /css
- `base.css` — global base styles  
- `theme.css` — optional theme layer  

### /js
- `utils.js` — small helpers shared across projects  

### /img
- `logo.svg` — brand mark  
- `icons/` — SVG or PNG icon set  

### /fonts
- font files plus `fonts.css` with `@font-face` rules  

### /media
- audio or video used in multiple projects  

---

## 🛠️ Guidelines

- Small page-specific files → keep them inside the project repo.  
- Shared or heavy assets → host here and load via jsDelivr.  
- Cache busting → update the tag (`v1.0.1`) or pin a commit hash.  
- CORS → jsDelivr sends `Access-Control-Allow-Origin: *`, so CodePen works.  

---

## 🚀 Use with jsDelivr

**URL format**

https://cdn.jsdelivr.net/gh/MechMadHog/mechmadhog-cdn@BRANCH_OR_TAG/PATH/TO/FILE

**Examples**
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/MechMadHog/mechmadhog-cdn@main/css/base.css">
<script src="https://cdn.jsdelivr.net/gh/MechMadHog/mechmadhog-cdn@main/js/utils.js"></script>
<img src="https://cdn.jsdelivr.net/gh/MechMadHog/mechmadhog-cdn@main/img/logo.svg" alt="Logo">
