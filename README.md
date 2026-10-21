# Naama Skital — Portfolio

Dark, responsive personal portfolio built with React, TypeScript and Vite.

## Run locally

```bash
npm install
npm run dev
```

Open the local address shown by Vite (typically http://localhost:5173).

## Build

```bash
npm run build
```

Deploy the `dist/` directory to Netlify, Vercel, or GitHub Pages (configure base path if hosting under a repository subpath). The site is not yet publicly deployed.

## Features

- Responsive mobile navigation, skip-to-content link, visible focus outlines, reduced-motion support
- Filterable/searchable projects, case-study dialogs and repository links
- Experience, education, skill areas, email and social links
- Four downloadable resume variants in `public/resumes/`

## Content checks before publishing

- Review all experience and project descriptions for accuracy.
- Topological Data Analysis is presented as coursework without a public repository link.
- LMY work is described at a non-confidential level.
- Project illustrations are abstract graphics, not screenshots of running demos.
- Add actual demo screenshots and repository links only when available.
- Accessibility is implemented in code but has not undergone a full automated or screen-reader audit.

## Environment note

Dependencies could not be installed in the current offline authoring environment, so a production build was not verified here. `npm install && npm run build` should be run in an internet-connected environment before deployment.
