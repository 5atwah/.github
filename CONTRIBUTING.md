# Contributing

## Purpose

These guidelines keep 5atwah work clear, reviewable, and build-ready.

## Source of Truth

Use the official `5atwah` GitHub organization for company work. Do not continue official work in old personal repositories.

Before meaningful work, read:

- `5atwah/foundation/SOURCE_OF_TRUTH.md`
- `5atwah/knowledge/AI_WORKING_RULES.md`
- `5atwah/standards/README.md`
- Relevant product docs in `5atwah/docs`
- Relevant standards in `5atwah/standards`

## AI and Codex Rules

AI tools and Codex sessions must:

- Work only in official `5atwah` repositories for official work.
- Check whether files already exist before creating them.
- Update existing files instead of creating duplicates when appropriate.
- Verify GitHub writes by reading files back after creation or update.
- Return changed paths and commit hashes when files are changed.
- Document unclear requirements as open questions instead of guessing.
- Avoid exposing internal promotion, fraud, or abuse protection logic to customers.

## Before Coding

Do not start real implementation until the relevant product logic, data model, acceptance criteria, and security rules are clear.

If a requirement is unclear, document it as an open question instead of guessing.

## Documentation Standards

- Keep documents structured with clear headings.
- Prefer build-ready rules over vague notes.
- Include Arabic and English considerations where product behavior or UI is affected.
- Consider Arabic RTL layout from the beginning.
- Do not add secrets, passwords, private keys, tokens, or sensitive credentials.

## Pull Requests

Every pull request should include:

- What changed.
- Why it changed.
- How it was checked.
- Any open questions or follow-up work.

For product logic changes, link or mention the relevant documentation.

## Commit Style

Use short, clear commit messages that describe the change. Examples:

- `Add order logic documentation`
- `Add inventory status rules`
- `Update business settings plan`
