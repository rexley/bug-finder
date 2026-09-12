# Bug Finder

A mobile-friendly browser app for scanning your home for small moving, bug-like objects.

## Features
- Live browser camera
- Red highlighting for higher-confidence bug-like movement
- Blue scanning overlay for background / lower confidence
- Take and save photos locally on the device
- Camera frames stay in the browser

## Live site
Once GitHub Pages is enabled for the `main` branch at `/ (root)`, the app is available at:

https://rexley.github.io/bug-finder/

## Camera requirements
Camera access requires HTTPS (or localhost). Open the GitHub Pages URL directly in Safari or Chrome and allow camera permission when prompted.

## Detection note
This version uses lightweight motion, contrast, and shape heuristics. It is not yet a trained insect-species recognition model, so camera shake, shadows, and textured surfaces can produce false positives.
