# wwirh.org

Source for "Who's Who in Riemann Hypothesis Research" at https://wwirh.org.
Sister site to wwigr.org. Same three-source pipeline (arXiv + OpenAlex + zbMATH),
retargeted to the Riemann hypothesis and the zeros of the zeta and L-functions.

`_site/` is the deployable static site; Cloudflare serves it as static assets
(see `wrangler.toml`). Every push to `main` auto-deploys.
