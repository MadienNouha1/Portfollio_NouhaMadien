# Developer Portfolio

A responsive, frontend-only React portfolio. Profile, social links, skills, education, experience, and project content are editable in `src/data.js`. Empty social, CV, repository, and demo links are intentionally hidden or shown as unavailable.

## Requirements

- Node.js 18 or newer
- npm

## Install and run

```sh
npm install
npm run dev
```

Open the local URL printed by Vite (usually `http://localhost:5173`).

## Contact form

The form validates its fields in the browser, then opens the visitor's default email app with the subject and message prefilled. It does not send or store messages itself. Update `profile.email` in `src/data.js` to your real address. A backend and SMTP configuration are not needed for this version.

## Build and deploy

```sh
npm run build
npm run preview
```

The static site is generated in `dist/`. Deploy that folder to any static hosting provider. No server, database, or environment secrets are required.

## Structure

```text
src/       React app, styles, and editable portfolio data
```
