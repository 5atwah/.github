# Security Policy

## Reporting Security Issues

Do not open public issues for security vulnerabilities.

For now, report security concerns privately to the 5atwah maintainers through the approved internal channel. A public security contact can be added later when the company support and security mailboxes are fully configured.

## Secret Handling

Never commit:

- Passwords.
- API keys.
- Access tokens.
- Private keys.
- Database credentials.
- Recovery codes.
- Customer personal data.
- Production logs containing sensitive information.

If a secret is committed by mistake, treat it as compromised and rotate it immediately.

## Access Principles

- Use least privilege for admin, support, finance, rider, supplier, and engineering access.
- Keep production access limited and auditable.
- Record important admin and operational changes in audit logs.
- Do not share accounts between people.

## Product Security Requirements

Security rules must be considered before implementation, including:

- Role permissions.
- Admin access limits.
- Support access limits.
- Payment and refund controls.
- Audit events.
- Backup and restore process.
- Incident response notes.
