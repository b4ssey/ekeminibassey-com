# ekeminibassey-com

Personal portfolio site. Built with [Hugo](https://gohugo.io/) and the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme.

## Run locally

```bash
hugo server
```

Open http://localhost:1313

## Build

```bash
hugo
```

Output is in `public/`.

## Deploy on Vercel

The theme is loaded via Hugo Modules. For a reliable build (including images), the project uses the [Vercel Hugo setup](https://www.rizkidoank.com/2024/02/26/deploy-hugo-to-vercel/):

- **Install command** (in `vercel.json`): installs Go so `hugo mod get` and image processing work.
- **Environment variables** (set in Vercel → Project → Settings → Environment Variables):
  - `HUGO_VERSION` – e.g. `0.155.1` (match your local Hugo version).
  - `HUGO_ENV` – set to `production`.
