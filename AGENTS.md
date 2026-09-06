# AGENTS.md

## Project

`@eliware/project-template` is a starter ESM Node.js application template using dotenv, `@eliware/common`, Jest, and linting.

## Development

- Use Node.js 26 and native ESM.
- Keep `.env.example` current and never commit `.env` or credentials.
- Preserve the documented clone, rename, install, start, test, and customization workflow.
- Keep application startup and shutdown examples safe and explicit.

## Validation

Run `npm ci` and `npm test` after template changes. Do not start services
unintentionally. Read `docs/README.md`, `specs/README.md`, and
`examples/README.md` before changing the corresponding material.

## Changes

Update README, environment examples, package metadata, and template files together. Do not bump versions, tag, publish, or deploy unless explicitly requested.
