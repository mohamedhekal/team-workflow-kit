# Security Policy

## Reporting a vulnerability

Please do not open a public issue for security problems. Use GitHub's private vulnerability reporting (Security tab, "Report a vulnerability") and include steps to reproduce.

You can expect an acknowledgement within 3 business days.

## Handling secrets

Never commit credentials, tokens or `.env` files. If a secret is committed by mistake, rotate it immediately; removing it from history is not enough.
