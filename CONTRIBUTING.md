# Contributing

Thanks for contributing to a FinHero Data repository. This is an internal org — these guidelines apply to employees and authorized contractors.

## Workflow

1. Create a branch off `main` (e.g. `feat/short-description`, `fix/short-description`).
2. Make your changes with clear, atomic commits.
3. Open a pull request using the provided template.
4. Ensure CI checks pass and request review from the relevant code owners.
5. Squash-merge once approved; delete the branch after merge.

## Commit messages

Keep them short and descriptive, focused on *why* rather than *what*. Reference issue numbers where relevant (`Fixes #123`).

## Code review

- Keep PRs small and scoped to one logical change.
- Respond to review comments promptly; resolve conversations before merging.
- CODEOWNERS are automatically requested for review based on the files changed.

## Data handling

Never commit real customer PII, credit data, credentials, or secrets to any repository, including in commit messages, issues, or PR descriptions. Use environment variables / secret managers for credentials, and synthetic/fixture data for tests and examples.

## Reporting bugs or requesting features

Use the issue templates provided in each repository (or inherited from this `.github` repo).

## Security issues

Do not file security vulnerabilities as public issues — see [SECURITY.md](SECURITY.md).
