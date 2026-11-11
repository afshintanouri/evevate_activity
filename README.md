# AI Learning Journey Designer

A static, browser-based workshop application for redesigning learning activities as deliberate journeys through four modes of human-AI collaboration: Enhance, Empower, Adopt and Shape.

## Publish on GitHub Pages

1. Create a new public GitHub repository.
2. Upload `index.html`, `styles.css` and `script.js` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. Open the Pages URL displayed by GitHub.

No build step, API key, database or backend is required.

## Customise

Quadrant names, descriptors and literacy labels are stored in the `CONFIG` object at the top of `script.js`. Change the bottom-right name there if the workshop framework evolves.

## Data and privacy

All responses are saved only to the participant's browser using `localStorage`. The app has a **Clear my data** control. No information is transmitted to a server.

## Export

The final Journey Plan can be printed or saved as PDF using the browser print dialog. A JSON backup can also be downloaded.
