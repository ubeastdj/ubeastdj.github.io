# IPNMP Standalone App

Vite + React standalone version of the WordPress Irrigated Pasture and Nitrogen Management calculator.

## Run locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
npm run preview
```

## Notes

- `src/App.jsx` contains the calculator engine, report layout, chart, PDF export, and shareable scenario URLs.
- Browser state is saved in localStorage.
- The app writes a compressed-ish scenario string into the URL so scenarios can be shared.
- PDF export uses `html2canvas` + `jspdf`.
