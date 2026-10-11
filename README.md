# Statement Calculator

Upload a text-based bank statement PDF to total debits and credits, switch individual
transactions on or off, and plan regular, one-time and KOKO payments for the rest of the year.

Everything runs in the browser. The PDF is never uploaded, and the payment list is kept in
the browser's local storage on the device you use. This repository contains no personal data.
Use **Reset all data** (bottom card) to clear what the app has saved on your device.

## Publish with GitHub Pages

1. In the repository open **Settings > Pages** and set **Source** to **GitHub Actions**.
2. The workflow in `.github/workflows/pages.yml` publishes `index.html` on every push to the
   default branch (and to `main`). To run it by hand, open **Actions > Deploy to GitHub Pages > Run workflow**.
3. The address is `https://<your-username>.github.io/AccountStatement/`.
