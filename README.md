# autrio.gay

Static site on Cloudflare Workers (static assets). Site files live in `public/`.

- Push to `main` → Cloudflare Workers Builds deploys to https://autrio.gay
- Push any other branch → preview URL (shown on the commit in GitHub)

## Local dev

```sh
npx wrangler dev        # http://localhost:8787, same as prod
# or: npx serve public
```

## Manual deploy

```sh
npx wrangler deploy
```
