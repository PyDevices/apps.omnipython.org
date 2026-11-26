# AGENTS.md

- Nothing here is the page itself: it's built by omnipython-builds (`scripts/build_wasm_allapps.py`, `.github/workflows/wasm-allapps.yml`), and a change to the page goes there.
- `publish.yml` deploys an `allapps-page` artifact from an omnipython-builds run to this repository's GitHub Pages site. Run it by hand with a run id to publish, or put back, a particular build.
- Never commit build output here. The custom domain is set in the repository's Pages settings, not by a `CNAME` file.
- A repository with a GitHub Pages site takes over `omnipython.org/<its name>/`, so this repository must never get a landing page on omnipython.org.
