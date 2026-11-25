# Persona: Beyond the Mask

An interactive fan-made site with P3, P4 and P5 sections. Open `index.html` in a browser.

All artwork is original placeholder art. Persona is a trademark of its respective owners; this project is not affiliated with or endorsed by them.

## Deploy to Cloudflare

No build step. Everything is static.

**Git integration (easiest):** Cloudflare dashboard > Workers & Pages > Create > Import a repository > pick `mikey101101/Persona`. Leave the build command empty. For Workers, the deploy command is `npx wrangler deploy` (uses `wrangler.jsonc`). For Pages, set the output directory to `/`.

**CLI:** `npx wrangler login` then `npx wrangler deploy`.

Note: a public deploy shows your key art and soundtrack to everyone. Keep the project private or use Cloudflare Access if you want it to stay personal.
