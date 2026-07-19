# Contributing

## Purpose

These guidelines keep 5atwah work clear, reviewable, and build-ready.

## Source of Truth

Use the official `5atwah` GitHub organization for company work. Do not continue official work in old personal repositories.

Before meaningful work, read:

- `5atwah/knowledge/START_HERE_5ATWAH_CONTEXT_INDEX.md`
- `5atwah/foundation/SOURCE_OF_TRUTH.md`
- Relevant product docs in `5atwah/docs`
- Relevant standards in `5atwah/standards`

For engineering or AI-assisted work, also read `5atwah/standards/ai/AI_WORKING_STANDARDS.md`.

## AI-Assisted Contributions

AI-assisted work starts at `5atwah/knowledge/START_HERE_5ATWAH_CONTEXT_INDEX.md` and follows
`5atwah/standards/ai/AI_WORKING_STANDARDS.md`. This guide does not duplicate that policy.

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

Use Conventional Commit messages. Examples:

- `docs: add order logic documentation`
- `fix: correct inventory status rule`
- `feat: add business settings plan`
