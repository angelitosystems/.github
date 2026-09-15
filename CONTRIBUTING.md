# Contributing to Angelito Systems

Thank you for your interest in contributing to projects maintained by Angelito Systems. This document describes the general process we follow across our repositories.

## Contents

- [Code of Conduct](#code-of-conduct)
- [Before opening a change](#before-opening-a-change)
- [Getting started](#getting-started)
- [Commit messages](#commit-messages)
- [Pull requests](#pull-requests)
- [Reporting issues](#reporting-issues)
- [Precedence](#precedence)

## Code of Conduct

By participating in this project, you agree to abide by our [Code of Conduct](./CODE_OF_CONDUCT.md).

## Before opening a change

1. Read the repository's README and any project-specific contribution guidelines.
2. Check open issues and pull requests to avoid duplicating existing work.
3. Keep changes focused and maintainable — prefer several small pull requests over one large one.
4. Add or update tests when behavior changes.
5. Document public APIs and relevant configuration.
6. Never commit secrets, credentials or private data.

## Getting started

1. Fork the repository and create a new branch from the default branch.
2. Use a descriptive branch name, e.g. `feature/short-description` or `fix/short-description`.
3. Install dependencies and run the project locally following the repository's README.
4. Make your changes, following the existing code style and conventions of the project.
5. Run the test suite and linters before opening a pull request, if available.

## Commit messages

- Write clear, descriptive commit messages in the imperative mood (e.g. "Add validation for user input").
- Keep the first line concise; use the body to explain the "why" when it isn't obvious.
- Reference related issues where relevant (e.g. `Fixes #123`).

## Pull requests

Please explain in your pull request description:

- **What** changed;
- **Why** it changed;
- **How** it was tested;
- Any **breaking or migration** considerations.

Keep pull requests scoped to a single concern where possible, and be responsive to review feedback — it helps us merge your contribution faster.

## Reporting issues

- Search existing issues before opening a new one.
- Provide clear reproduction steps, expected vs. actual behavior, and relevant environment details.
- For security vulnerabilities, follow [SECURITY.md](./SECURITY.md) instead of opening a public issue.

## Precedence

Project-specific rules take precedence over this organization-level document.