# beatingu.com

Landing page for the BeatingU family of iPhone games (BBG Studios LLC).

- Plain HTML/CSS, no build step. Preview: `python3 -m http.server 8001`, then http://localhost:8001
- Deployed by Cloudflare Workers Builds on every push to `main` (`npx wrangler deploy`, config in `wrangler.jsonc`).
- `.assetsignore` keeps repo-only files off the live site. Add any new non-public root file there.
- App detail pages and privacy policies live on brendangaynor.com and are linked from here.
