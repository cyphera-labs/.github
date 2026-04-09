# Contributing to Cyphera

Thanks for your interest in contributing to Cyphera.

## Getting Started

1. Fork the repository
2. Create a feature branch (`git checkout -b feat/my-feature`)
3. Make your changes
4. Run tests (see each repo's README for language-specific instructions)
5. Commit with a descriptive message
6. Push and open a Pull Request

## Pull Request Expectations

- Tests pass
- Code follows existing patterns in the repo
- One logical change per PR
- Describe what and why in the PR description

## Reporting Issues

Use the issue templates provided. Include:
- What you expected to happen
- What actually happened
- Steps to reproduce
- Language/version/platform

## Cross-Language Compatibility

Cyphera SDKs must produce identical output across all languages for the same inputs. If you're modifying encryption logic, verify your change passes the cross-language test vectors in the `cyphera-test-vectors` repo.

## License

By contributing, you agree that your contributions will be licensed under the Apache License 2.0.
