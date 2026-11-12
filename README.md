# Continera Key Control

A lightweight PWA-style key control simulator for the **DAF XG+ 530**.

## Current functionality

- Visual cabin panel with steering wheel and ignition-key lock positioned to its right.
- Insert and remove the key with a simple visual transition.
- Key state is saved in `localStorage` and restored after reopening the app.
- Web app manifest and service worker for installability and offline caching.

## Scope

This project simulates **only inserting and removing the key**. It does not start the engine or simulate ignition positions.

## Run locally

Serve the repository with a local HTTP server (for example, VS Code Live Server), then open the page in a browser. Service workers and PWA installation do not work from a plain `file://` URL.

## Files

- `index.html` — interface, styles, and interaction logic.
- `manifest.json` — PWA metadata.
- `sw.js` — offline cache and service worker.
