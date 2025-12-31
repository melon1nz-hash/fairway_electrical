# Fairway Electrical Website

A modern, responsive, static one-page website for Fairway Electrical.

## 🔧 Technology Stack
*   **HTML5**: Semantic markup for structure.
*   **CSS3**: Custom properties (variables), Flexbox, and Grid for styling. No frameworks.
*   **JavaScript**: Vanilla JS for mobile menu and scroll effects.
*   **Decap CMS**: Pre-configured for Netlify deployment.

## 🚀 How to Run locally
1.  Open `client/index.html` in your browser.
2.  Or use a simple static server (e.g., `python3 -m http.server` inside the `client` folder).

## 📦 Deployment (Netlify)
1.  **Build Settings**:
    *   **Publish directory**: `client` (or `.` if you push the client folder contents to root)
    *   **Build command**: (None required for pure static, or `npm run build` if you want to use the legacy vite setup)

## 📁 Folder Structure
```
/
├── index.html          # Main homepage
├── css/
│   └── style.css       # All styles
├── js/
│   └── main.js         # Mobile menu & interactions
├── images/             # Local static assets
└── admin/              # Decap CMS configuration
    ├── index.html
    └── config.yml
```
