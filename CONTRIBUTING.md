# Contribution guide

Thank you for your interest in contributing to Quarzum!

This document explains how to start contributing to this project.

## Content table

1. [First steps](#first-steps)
2. [Environment configuration](#environment-configuration)
3. [Code style and conventions](#code-style-and-conventions)
4. [Testing](#testing)
5. [Pull Requests](#pull-requests)

## First steps

### Before contributing

- Check the existing issues
- Look for issues tagged as "good first issue"
- Read [README.md](./README.md)

### First commits

1. **Fork** this repository
2. **Clone** your fork locally
3. **Create a branch** with a descriptive name:

```
git checkout -b feat/add-new-feature
```

> [!TIP]
> Please use **conventional commits** to name your commits

### Environment configuration

- Language: Quarzum (latest version)
- Supported operating systems: Linux

## Code style and conventions

- Use PascalCase for structs and tuple names
- Use camelCase for variables and functions
- Use the `.test.qz` extension for test files
- Use SCREAMING_SNAKE_CASE for global constants

## Pull requests

When your contribution is finished, open a new pull request. Make sure that each test passes successfully. Also make sure to update documentation and CHANGELOG.md if it is a breaking change.
