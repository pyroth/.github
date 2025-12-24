# Contributing

## Code of Conduct

By participating, you agree to follow our [Code of Conduct](CODE_OF_CONDUCT.md).

## Before You Start

- **Search existing issues** to avoid duplicates.
- **Use the provided templates** for issues and pull requests.
- **Share enough context** for others to reproduce, review, and maintain your change.

## Issues

### Bug Reports

Include:

- **Steps to reproduce**
- **Expected vs. actual behavior**
- **Environment** (OS, version, logs, screenshots if relevant)

### Feature Requests

Include:

- **Problem statement**
- **Proposed approach** (optional)
- **Alternatives / trade-offs** (if applicable)

## Pull Requests

- **Base branch**: `main`
- **Scope**: keep changes focused and reviewable
- **Quality**: add tests when applicable; update docs when behavior changes
- **Commits**: use clear messages (see below)
- **Template**: complete the pull request template

## Workflow

1. Fork and clone
2. Create a branch: `git checkout -b feature/<name>`
3. Implement changes
4. Commit: `git commit -m "feat: <summary>"`
5. Push: `git push origin feature/<name>`
6. Open a Pull Request

## Commit Messages

Follow [Conventional Commits](https://www.conventionalcommits.org/):

- `feat:` new feature
- `fix:` bug fix
- `docs:` documentation only
- `refactor:` refactoring without behavior change
- `test:` tests
- `chore:` tooling / maintenance

## Review

- All changes require review before merge.
- Address feedback with follow-up commits.

## Security

For security issues, follow [SECURITY.md](SECURITY.md).
