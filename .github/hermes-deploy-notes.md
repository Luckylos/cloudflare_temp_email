# Hermes deployment notes

This fork is configured for Cloudflare GitHub Actions deployment.

- Backend workflow: `.github/workflows/backend_deploy.yaml`
- Worker name/domain/D1/KV are supplied via repository Actions secrets.
- Do not commit production secrets into `wrangler.toml`.
