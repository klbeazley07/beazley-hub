# beazley-hub

The landing page for beazley.app — a family software platform.

Single static HTML file. Deployed via Cloudflare Pages, auto-deployed
on push to main.

## Live
- Production: https://beazley.app
- Preview: https://beazley-hub.pages.dev

## Editing
Edit index.html directly. Push to main. Cloudflare deploys automatically.

## Project status
When a Beazley project moves from Building to Live, update the
corresponding card in index.html:
- Change `class="card building"` to `class="card live"` and make it
  an `<a>` element with href to the project subdomain
- Change the status text from "Building" to "Live"
- Change the arrow character from "·" to "→"
