# ianwschneider.com

Ian W. Schneider's portfolio site. Static HTML and CSS in `public/`, served by a Cloudflare Worker with static assets.

- `public/index.html` is the site. `public/resume.html` is the printable resume.
- `wrangler.jsonc` configures the Worker and the custom domains.
- Pushing to `main` redeploys through Cloudflare's Git integration.

To add a video, replace a `.frame.pending` block in `index.html` with a `.frame.yt` block (see the Kyle Gordon entry) and set `data-id` to the YouTube ID.
