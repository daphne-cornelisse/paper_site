# Human-like autonomy paper site

Static project website for:

**Human-like autonomy emerges from self-play and a pinch of human data**

## Local preview

Open `index.html` directly in a browser, or run:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy on Vercel

This is a plain static site. In Vercel, import the GitHub repo and use:

- Framework preset: `Other`
- Build command: leave empty
- Output directory: `.`

Vercel will serve `index.html` from the repository root.

For a more descriptive default Vercel URL, rename the Vercel project to
something like `human-like-autonomy` or `hla-self-play` if the subdomain is
available. A custom domain can also be added from the Vercel project settings;
that cannot be controlled from this static repo alone.

The `reg_self_play_pufferdrive_demos/` directory contains the rollout media
referenced by the site.
