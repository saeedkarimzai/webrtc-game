# WebRTC Minecraft Browser Game

This repository contains the single-page game in `real_mc.html`. The root `index.html` redirects to it for GitHub Pages.

## Important dependency

The game file currently has a `<base href="https://16f81.codesandbox.io">` entry. Its relative game assets are loaded from that external CodeSandbox host, not from this GitHub repository. The repository currently contains only the HTML file, so it is **not a self-contained/offline build**. If the original CodeSandbox deployment is unavailable, the game will not fully load until its missing asset tree is exported and committed here.

## Run

Publish the repository with GitHub Pages (Settings → Pages → Deploy from a branch → main → /(root)), then open the site. Internet access is required for the remote assets and any external services.
