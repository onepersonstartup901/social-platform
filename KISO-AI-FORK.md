# KISO AI Fork of Postiz

This repository is a fork of [gitroomhq/postiz-app](https://github.com/gitroomhq/postiz-app), maintained by KISO AI for internal use.

## What changed in this fork

- Branding: app name set to "KISO AI" in user-visible strings (logo + favicon + OG image pending)
- Production deploy: docker-compose targeting Hetzner Cloud + Caddy
- Public signup: disabled via `DISABLE_REGISTRATION` env var (postiz built-in)
- Two seeded admin accounts: Daichi, Fabian

## License

Same as upstream: AGPL-3.0. This fork is public to pre-satisfy AGPL source-disclosure obligations if the platform is ever exposed to non-internal users.

## Upstream

To pull upstream changes:

```bash
git fetch upstream
git merge upstream/main
```

Resolve conflicts in branding files by keeping our versions.

## Production deploy

See `/Users/ai-sandpit/Desktop/Command HUB/Business/AI Edu - JP + GER/deploy/social-platform/` in the KISO AI workspace for production docker-compose, Caddyfile, and backup scripts.
