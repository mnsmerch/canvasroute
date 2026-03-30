# CanvasRoute — Paint Pals Canvassing Tool

A door-to-door canvassing route planner with cloud-synced route storage via Firebase Firestore.

## Features
- Google Maps route planning with draggable pins
- Auto address lookup via Google Geocoding
- Save/load routes to Firebase cloud (never lose data)
- Review results per stop (Lead, Not Home, etc.)
- Shift timing and canvassing reports
- Print route map + address sheet

## Deploy to Vercel

1. Push this folder to a GitHub repo
2. Go to [vercel.com](https://vercel.com) → Import Project → select your repo
3. No build settings needed — it's a static HTML file
4. Hit Deploy

## Firebase Setup
Already configured for `paintpals-canvasroute` Firebase project.

If you need to update Firebase credentials, edit the `FIREBASE_CONFIG` object in `index.html`.

## Google Maps API
Already configured. If you need to update the key, search for `AIzaSyDkGH` in `index.html`.
