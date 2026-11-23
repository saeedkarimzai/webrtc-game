# WebRTC Minecraft Browser Game

This repository contains a browser-hosted Minecraft-style game in `real_mc.html`. The root `index.html` redirects to it for GitHub Pages.

## Run

Publish the repository with GitHub Pages (Settings → Pages → Deploy from a branch → main → /(root)), then open the HTTPS site. The game loads its original JavaScript and media assets from a pinned public snapshot of the upstream project. Internet access is required.

## Important limitations

- The game is not a self-contained or offline build. Its upstream asset snapshot is hosted outside this repository.
- Multiplayer login, world discovery, and WebSocket sessions still rely on the original third-party service at `server.nathaniel2006.repl.co`. This repository does not operate that service, so multiplayer may be unavailable even when single-player loads.
- Browser WebGL and audio support are required. Some school networks block external assets or WebSocket connections.
- The original game source is from [sakuzyokun/sakuzyokun.github.io](https://github.com/sakuzyokun/sakuzyokun.github.io), pinned to commit `050c6022834299ade38b5d31fb4a90ef455a2b6b`.

This is a browser game experiment, not an official Minecraft product.
