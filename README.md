# builtformca-site

Landing page for [builtformca.com](https://builtformca.com) — the BuiltForMCA brand portfolio,
showcasing five SaaS products for the MCA industry: DealHub, BlastWiz, Genie, TrackMyCM, and Deal Intake.

## Structure

- `index.html` — the entire site (single static HTML file, no build tooling)
- `public/` — static assets (favicons, OG image)

## Deployment

Deployed to Vercel. `vercel.json` copies `index.html` into `public/` at deploy time and serves
`public/` as the output directory, so the page and its assets all resolve from the site root.

Pushes to `main` auto-deploy once the repo is connected to the Vercel project.
