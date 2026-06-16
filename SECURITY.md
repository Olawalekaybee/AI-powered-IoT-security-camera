# Security Policy

## Supported versions

Security fixes are applied to the latest version on the `main` branch.

## Reporting a vulnerability

Please do not open public GitHub issues for security-sensitive problems. Report vulnerabilities privately to the repository owner.

## Deployment security notes

- Do not expose the Flask development server directly to the public internet.
- Use Tailscale, VPN, reverse proxy authentication, or another private access layer.
- Change `SECRET_KEY` before production use.
- Never commit `.env`, WiFi credentials, API keys, Tailscale auth keys, SSH keys, or private model assets.
