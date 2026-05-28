# Nityay Bhavsar — Portfolio Website

A cyberpunk terminal-aesthetic portfolio with a Three.js 3D developer avatar.

## 🚀 Deploy to GitHub Pages

### Step 1 — Create the repo
1. Go to [github.com](https://github.com) and create a **new repository**
2. Name it exactly: `<your-username>.github.io`
   - Example: `Nityayyrrr.github.io`
3. Set it to **Public**

### Step 2 — Add your files
Upload these two files to the repo root:
- `index.html`
- `Resume_with_cgpa__1_.pdf` (rename to this if needed, or update the href in index.html)

### Step 3 — Enable GitHub Pages
1. Go to repo **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: **main** / root `/`
4. Click **Save**

### Step 4 — Live in ~2 minutes
Your site will be live at: `https://Nityayyrrr.github.io`

---

## 📝 Customization Guide

### Update your resume download link
In `index.html`, find this line and update the filename:
```html
<a href="Resume_with_cgpa__1_.pdf" download="Nityay_Bhavsar_Resume.pdf" ...>
```

### Add your GitHub project links
Search for `href="https://github.com/Nityayyrrr"` and replace with direct repo URLs.

### Change 3D model colors
In the Three.js section, look for `matCyan`, `matPurple`, `matGreen` to change colors.

### Update contact form
The form opens your mail client. To use a real form backend, replace `handleFormSubmit` with a fetch to Formspree or EmailJS.

---

## 🛠 Tech Stack
- **Three.js r128** — 3D scene, developer avatar, particles
- **Vanilla JS** — typed effect, scroll reveal, cursor
- **CSS custom properties** — theming, animations
- **Google Fonts** — Orbitron (display), Share Tech Mono, Inter
- **No build step** — deploy as-is!
