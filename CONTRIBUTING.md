# Contributing to Orange Cat Lang

Thank you for your interest in contributing to Orange Cat Lang!

We welcome bug reports, feature requests, documentation improvements, and code contributions.

---

## Table of Contents

- Prerequisites
- Development Setup
- Project Structure
- Development Workflow
- Coding Standards
- Testing
- Commit Messages
- Pull Requests
- Reporting Bugs
- Requesting Features
- License

---

## Prerequisites

Before contributing, ensure you have:

- Bun
- Git
- TypeScript

---

## Development Setup

Clone the repository:

```bash
git clone https://github.com/orangecatprog/orange-cat-lang.git
```

Install dependencies:

```bash
bun install
```

---

## Development Workflow

1. Create a new branch.
2. Implement the feature or fix.
3. Write or update tests.
4. Run all checks.
5. Open a Pull Request.

---

## Coding Standards

Orange Cat Lang follows:

- Clean Architecture
- Screaming Architecture
- Class-Contract Architecture
- SOLID principles
- Test-Driven Development (TDD)

All code should be:

- Small
- Readable
- Maintainable
- Well documented

---

## Testing

Run all tests:

```bash
bun test
```

Run coverage:

```bash
bun run test:coverage
```

---

## Linting & Formatting

Lint:

```bash
bun run lint
```

Format:

```bash
bun run format
```

Verify formatting:

```bash
bun run format:check
```

---

## Commit Messages

This project uses:

- Conventional Commits
- Commitlint
- Commitizen

Create commits using:

```bash
bunx cz
```

---

## Pull Requests

Before opening a Pull Request:

- Ensure all tests pass.
- Ensure lint passes.
- Ensure formatting passes.
- Update documentation if necessary.
- Add tests for new functionality.

---

## Reporting Bugs

Please use the Bug Report issue template.

---

## Requesting Features

Please use the Feature Request issue template.

---

## License

By contributing to this project, you agree that your contributions will be licensed under the MIT License.
