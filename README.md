# TEMUSAN SPACE — Web Rhythm Game Prototype

## Included
- `index.html`: single-page web game (HTML/CSS/JavaScript, Canvas 2D perspective rendering)
- `assets/Sky 2.mp3`: first test track supplied for this prototype

## Play locally
Open `index.html` in a modern browser. If the browser blocks local audio loading, run a small local server from this folder (for example, VS Code Live Server) or use GitHub Pages.

## Publish with GitHub Pages
1. Open the repository `temusan_rhythm_game`.
2. Choose **Add file → Upload files**.
3. Upload `index.html` and the `assets` folder (keep the folder structure).
4. Commit the upload to the `main` branch.
5. Open **Settings → Pages**.
6. Under **Build and deployment**, select **Deploy from a branch**, branch `main`, folder `/(root)`, then Save.
7. Wait for deployment and open the URL shown in the Pages section.

## Controls
Move the mouse cursor over a note as it reaches its timing window. No click is required during gameplay.
Use **PLAY GAME → PLAY THIS SONG** to start the audio; browser audio requires a user interaction.

## Notes
- The starter chart is automatically generated using an approximate tempo estimate of 129 BPM. It is a playable prototype chart, not a hand-authored or beat-perfect chart.
- Song length is configured to approximately 98.8 seconds.
- The current version uses 2D Canvas drawing to create a 3D-like perspective effect, and does not require Unity or a build step.
