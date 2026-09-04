# OpenSA browser build

This repository deploys an unmodified browser build of OpenSA from the public upstream repository:

- Upstream: https://github.com/AlexSergey/opensa
- License: AGPL-3.0-only
- Purpose here: run the OpenSA browser engine from GitHub Pages and let the user provide their own legitimate GTA: San Andreas files locally through the browser.

No Rockstar Games / Take-Two game assets are stored in this repository or included in the Pages deployment.

The deployment workflow checks out the current upstream `main` branch at build time, installs its dependencies, runs the upstream production build with the GitHub Pages base path `/Linitesgpt/`, and deploys only the generated web application.
