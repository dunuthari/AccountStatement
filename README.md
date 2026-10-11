# Statement Calculator

Upload a text-based bank statement PDF to total debits and credits, switch individual
transactions on or off, and plan regular, one-time and KOKO payments for the rest of the year.

Everything runs in the browser. The PDF is never uploaded, and the payment list is kept in
the browser's local storage on the device you use. Use **Reset all data** (bottom card) to clear it.

## Publish with GitHub Pages

1. Merge this branch into `main`.
2. In the repository go to **Settings > Pages** and set **Source** to **GitHub Actions**.
3. The workflow in `.github/workflows/pages.yml` publishes `index.html` on every push to `main`.
   The address is `https://<your-username>.github.io/AccountStatement/`.
