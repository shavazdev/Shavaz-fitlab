# SHAVAZ FIT LAB

Track. Train. Transform.

A free, private, open-source fitness tracker (PWA) for fat loss, strength and healthy habits. No account, no server, no tracking. Everything is stored in the browser on your device.

## Features
Weight trend, measurements, Push/Pull/Legs workouts with PRs and 1RM graphs, Indian food database with protein and fiber, steps, water, recovery, weekly check-in, plateau check, PIN lock, dark/light mode, JSON/CSV export and import, voice logging (Chrome), optional AI photo food scan (bring your own API key).

## Files
- `index.html` landing page
- `app.html` the app (single file, plain HTML/CSS/JS, no build step)
- `manifest.webmanifest`, `sw.js`, `icon-*.png` PWA install and offline support

## Run locally
Serve the folder over HTTP, for example `python3 -m http.server`, and open `http://localhost:8000`.

## Deploy free with GitHub Pages
Upload all files to a public repository, then Settings > Pages > Deploy from branch `main` / root. Your site appears at `https://USERNAME.github.io/REPO/`.

## Privacy
Data stays in your browser (localStorage). Voice input uses your browser's speech service. The photo scan, if you add your own Anthropic API key, sends the photo to Anthropic. Back up with Settings > Export JSON.

## Disclaimer
General fitness tracking only, not medical advice. Calorie and body-fat figures are estimates.

## License
MIT. See `LICENSE`.

## Contributing
Issues and pull requests are welcome. Keep the app dependency-free (plain HTML, CSS and JavaScript) and privacy-first: no analytics, no trackers, and never commit API keys.

## Roadmap
- Native Android build with automatic steps (Health Connect) and reliable reminders
- Full Hindi interface
- Optional encrypted cloud backup
