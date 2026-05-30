# OmegaMaster - Two-Page High-Fidelity Clone

This repository combines the OMEGA Clearspace and OMEGA Space Sustainability interactive pages into a single, unified website.

## 🚀 Live Pages
- **Clearspace (Home):** [/](https://OmegaMaster-realsamiul.vercel.app/) (or `/clearspace`)
- **Space Sustainability:** [/space](https://OmegaMaster-realsamiul.vercel.app/space)

## 🛠️ Features Implemented
1. **Sound Removal:** The ambient audio layer and mute button UI have been cleanly decoupled and removed from the Clearspace page.
2. **Multi-Page Architecture:** Both sites coexist as sibling pages (`index.html` and `space.html`) sharing the same root asset structure.
3. **WebGL Fix:** All textures and models are mapped to both root and nested paths to ensure 100% 3D visibility on Vercel deployments.

## 🏃 Local Development
```bash
python3 -m http.server 8000
```
