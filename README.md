# RCM Church Vizianagaram

A lightweight interactive 3D church and community website concept for RCM Church, Vizianagaram.

## Features

- Interactive 3D church campus model
- Drag, rotate and zoom controls
- Day and night visual modes
- 160-year heritage presentation
- Sunday and weekday Mass schedule sections
- Community meetings, music rehearsals and Bible-story content
- Google Maps location link
- Responsive single-page design

## Run locally

Serve the repository with a small local web server because the 3D scene uses browser modules.

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

The project is ready for static hosting through GitHub Pages, Netlify or Vercel. The main website is contained in `index.html` and loads Three.js modules from a CDN.
