# WebGL Cloth Physics Demo

An interactive 3D simulation of cloth hanging on a clothesline, blown around by wind from a desk fan. It runs in the browser using WebGL.

**Live demo:** https://madhevansasi944-eng.github.io/webgl-cloth-physics-demo/
(Update this link if you rename the repo.)



## Features
- Cloth simulation using position-based (Verlet) dynamics
- 3D desk fan that produces wind forces on the cloth
- Real-time rendering in the browser with WebGL
- Responsive page with a clean UI

## Tech Stack
- JavaScript, React
- WebGL
- Vite (build tool)
- GitHub Pages (hosting)

## How It Works
The cloth is a grid of points connected by constraints. On every frame:
1. Each point moves based on its previous position (Verlet integration).
2. Wind and gravity forces are applied to the points.
3. Constraints pull neighboring points back to their fixed distance, which keeps the fabric from stretching.

## About This Project
This project was built with AI assistance. I directed the design, tested and iterated on the result, and deployed it to GitHub Pages. This repo contains the compiled build output only.

## Run Locally
```bash
git clone https://github.com/madhevansasi944-eng/cloth-with-fan.git
cd cloth-with-fan
# open index.html in your browser
```

## Author
Madhevan Sasi ([@madhevansasi944-eng](https://github.com/madhevansasi944-eng))
