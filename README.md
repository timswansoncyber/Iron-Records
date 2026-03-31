# Iron Record

GitHub Pages-ready PWA bundle for the workout tracker.

## Files

- `index.html` - main app
- `manifest.webmanifest` - install metadata
- `service-worker.js` - offline cache
- `icons/` - app icons for install prompts and iPhone home screen
- `.nojekyll` - tells GitHub Pages to serve the site as a plain static bundle

## Deploy To GitHub Pages

1. Create a new GitHub repository.
2. Upload everything in this folder to the repository root.
3. In GitHub, open `Settings` -> `Pages`.
4. Under `Build and deployment`, choose `Deploy from a branch`.
5. Select the `main` branch and the `/ (root)` folder.
6. Save and wait for GitHub Pages to publish the site.

## Install On iPhone

1. Open the GitHub Pages URL in Safari.
2. Tap `Share`.
3. Tap `Add to Home Screen`.

## Important Data Note

Workout data is still stored locally in the browser on each device using IndexedDB. The app is installable and works offline, but it does not yet sync data between devices.
