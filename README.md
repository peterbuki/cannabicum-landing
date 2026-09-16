# cannabicum-landing

Landing page for Cannabicum built with Astro and TypeScript.

## Development

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Firebase Hosting deployment

The GitHub Actions workflow at `.github/workflows/firebase-hosting.yml` builds the Astro site and
deploys the generated `dist/` folder to Firebase Hosting on pushes to `main`.

Configure these GitHub settings before enabling the workflow:

- Repository variable: `FIREBASE_PROJECT_ID`
- Repository secret: `FIREBASE_SERVICE_ACCOUNT`
