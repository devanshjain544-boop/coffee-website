# Aurelia Coffee — 3D Artisanal Coffee House Experience

A luxury specialty coffee web application featuring interactive 3D WebGL visuals (Three.js), an agency-style 3D interactive laptop viewport, smooth scroll storytelling, and a shopping cart with Indian Rupee rates (`₹`).

## Features
- **Cinematic Hero**: Dark luxury aesthetic, warm gold typography, and smooth transitions.
- **3D Interactive Laptop Experience**: 5 interactive chapters with scroll-driven transitions, ambient lighting, and particle effects.
- **Product Collection**: Featuring Aurelia Classic (₹749), Aurelia Dark Roast (₹799), and Aurelia Signature (₹899) with interactive Quick-View modals.
- **Ritual Cart Drawer**: Dynamic subtotal and estimated total calculated in Indian Rupees (`₹`).
- **Agency Perspective Mode**: Preset camera angles (Cinematic 3D, Isometric, Subtle Tilt, Mouse Parallax).

## Getting Started

### Prerequisites
- [Node.js](https://nodejs.org) (v18 or higher recommended)
- npm or yarn

### Installation
```bash
# 1. Install dependencies
npm install

# 2. Run local development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Build for Production
```bash
npm run build
```
The production assets will be built in the `dist/` directory.

## Deploying to GitHub & Vercel
1. Create a repository on GitHub.
2. Push this project to your repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit of Aurelia Coffee"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
   git push -u origin main
   ```
3. Import the repository in [Vercel](https://vercel.com) or [Netlify](https://netlify.com) for instant 1-click free hosting.
