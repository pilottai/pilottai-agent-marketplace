# Contributing to PilottAI

First off, thank you for considering contributing to PilottAI! This document provides guidelines and instructions for contributing to the project.

## Table of Contents
- [Code of Conduct](#code-of-conduct)
- [Getting Started](#getting-started)
  - [Development Setup](#development-setup)
  - [Project Structure](#project-structure)
- [Development Process](#development-process)
  - [Creating a Branch](#creating-a-branch)
  - [Making Changes](#making-changes)
  - [Testing](#testing)
  - [Documentation](#documentation)
- [Pull Request Process](#pull-request-process)
- [Coding Standards](#coding-standards)
- [Community](#community)

## Code of Conduct

This project and everyone participating in it is governed by our Code of Conduct. By participating, you are expected to uphold this code. Please report unacceptable behavior to [conduct@pilottai.com](mailto:conduct@pilottai.com).

## Getting Started

### Creating a Branch

- Create branches from `main` for all changes
- Use meaningful branch names following this pattern:
  - `feature/description` for new features
  - `fix/description` for bug fixes
  - `docs/description` for documentation changes
  - `refactor/description` for code refactoring

```bash
git checkout -b feature/your-feature-name
```

### Making Changes

1. Make focused, incremental changes
2. Follow the [coding standards](#coding-standards)
3. Update tests and documentation as needed
4. Commit regularly with clear messages:


### Documentation

- Update relevant documentation in the `docs/` directory
- Add docstrings to new functions and classes
- Include usage examples for new features

## Pull Request Process

1. **Before Submitting**
   - Ensure all tests pass
   - Check code coverage
   - Run linting and type checking
   - Update documentation
   - Rebase on latest main

2. **PR Template**
   - Fill out the PR template completely
   - Link related issues
   - Describe your changes thoroughly
   - Include screenshots for UI changes

3. **Review Process**
   - At least one maintainer review is required
   - Address review comments promptly
   - Keep PR scope focused

## Coding Standards

### Python Style Guide

- Follow PEP 8 guidelines
- Use type hints for all functions
- Maximum line length: 88 characters
- Use descriptive variable names

## Community

- Join our [Discord](https://discord.gg/pilottai) <!-- TODO: Correct link -->
- Follow us on [Twitter](https://twitter.com/pilottai)
- Subscribe to our [newsletter](https://pilottai.com/newsletter)

## Questions or Need Help?

- Check our [documentation](https://docs.pilottai.com)
- Ask in our [Discord](https://discord.gg/pilottai) <!-- TODO: Correct link -->
- Open a [discussion](https://github.com/pilottai/pilott/discussions)

Thank you for contributing to PilottAI! 🚀
