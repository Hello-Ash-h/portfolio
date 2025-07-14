# 3D Portfolio Website

This is a simple, responsive portfolio website showcasing an interactive 3D model using [Three.js](https://threejs.org/). The site references assets stored within the repository.

## File Structure

```
assets/
  model.glb               3D model displayed in the hero
  photo1.png              Sample image used across sections
  screen-recording.mp4    Original screen recording of previous site
styles/style.css          CSS styles
scripts/main.js           JavaScript logic with Three.js
index.html                Main HTML
```

## Setup

1. Install [Node.js](https://nodejs.org/) (for optional local server).
2. Install dependencies:

```bash
npm install three
```

3. Start a simple local server (optional):

```bash
npx http-server .
```

Then open `http://localhost:8080` in your browser.

## Deploying

You can deploy the `index.html` and accompanying files to any static hosting platform such as GitHub Pages, Vercel, or Netlify. Ensure the `assets`, `styles`, and `scripts` folders remain at the same relative paths.
