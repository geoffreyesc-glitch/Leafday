# Leafday

A friendly, static houseplant-care web app for ten plants. It runs without a build step and is ready for static hosting.

## Run locally

Open `index.html` in a browser, or serve this folder with any static web server.

## What is included

- A responsive plant selector and detailed care guide for every plant.
- Sections for watering, fertilising, light, soil, best spot, and watch-outs.
- A small local care log: use the “Log” button in each care view to save the date in your browser. The care-history button collects those entries.
- Add a plant in one step: enter its name and Leafday creates a care guide from its common plant family (succulents, aroids, moisture-loving foliage, or a thoughtful general guide). Added plants stay saved in that browser.
- Remove a plant from its care guide’s **Remove plant** control. After confirmation, Leafday removes the plant and its saved care history from that browser.
- Plant details live in `app.js` as data objects, deliberately separated from rendering code. A hosted version can replace `getLogs` / `logCare` with a database service and calculate reminders using per-plant care rules.

## Hosting

Upload the folder to any static hosting provider (for example GitHub Pages, Netlify, or Vercel). No server is currently required; care log entries are saved in the browser’s local storage.
