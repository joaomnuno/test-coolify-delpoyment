# test-coolify-delpoyment

Minimal Dockerized app for testing Coolify GitHub deployment status syncing.

## Files

- `Dockerfile`: serves the `public/` directory with `nginx:alpine`
- `public/index.html`: trivial static page for main and preview deployment checks

## Suggested test flow

1. Deploy `main` in Coolify.
2. Push a small change to confirm GitHub deployment statuses update.
3. Open a PR changing the page text to verify preview deployments.
