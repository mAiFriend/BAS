# Contributing to Binary AI Scrum (BAS)

Thank you for considering contributing to the Binary AI Scrum project! This document outlines the process for contributing to this project and helps ensure a smooth collaboration.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Getting Started](#getting-started)
- [How to Contribute](#how-to-contribute)
  - [Reporting Bugs](#reporting-bugs)
  - [Suggesting Enhancements](#suggesting-enhancements)
  - [Pull Requests](#pull-requests)
- [Style Guidelines](#style-guidelines)
  - [Code Style](#code-style)
  - [Documentation Style](#documentation-style)
  - [Commit Messages](#commit-messages)
- [Project Structure](#project-structure)
- [Development Workflow](#development-workflow)
- [Community](#community)

## Code of Conduct

This project and everyone participating in it is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## Getting Started

1. **Fork the repository** on GitHub
2. **Clone your fork**:
   ```bash
   git clone https://github.com/YOUR-USERNAME/BAS.git
   cd BAS
   ```
3. **Set up the development environment**:
   ```bash
   pip install -r requirements-dev.txt
   ```
4. **Create a branch** for your feature or bugfix:
   ```bash
   git checkout -b feature/your-feature-name
   ```

## How to Contribute

### Reporting Bugs

We use GitHub issues to track bugs. Report a bug by [opening a new issue](https://github.com/mAiFriend/BAS/issues/new?template=bug_report.md).

When reporting bugs, please include:
- A clear, descriptive title
- Steps to reproduce the issue
- Expected behavior
- Actual behavior
- System information (OS, Python version, etc.)
- Any relevant logs or screenshots

### Suggesting Enhancements

Enhancement suggestions are also tracked through GitHub issues. [Open an enhancement issue](https://github.com/mAiFriend/BAS/issues/new?template=feature_request.md) with:

- A clear, descriptive title
- Detailed description of the proposed enhancement
- Any potential implementation approaches you're considering
- Explanation of why this enhancement would be valuable to the project

### Pull Requests

1. **Update your fork** to keep it in sync with the main repository
2. **Create a branch** with a descriptive name
3. **Make your changes**, following the style guidelines
4. **Write tests** for your changes when applicable
5. **Run tests** to ensure your changes don't break existing functionality
6. **Submit your pull request** with a clear description of the changes

Pull request titles should follow the pattern: `[COMPONENT] Brief description`

Example: `[Handshake Protocol] Add capability negotiation mechanism`

## Style Guidelines

### Code Style

- We follow PEP 8 for Python code
- Use meaningful variable and function names
- Keep functions focused on a single responsibility
- Document all public functions, classes, and modules

### Documentation Style

- Use Markdown for documentation
- Code examples should be properly formatted in code blocks
- Keep explanations clear and concise
- Include diagrams when they enhance understanding

### Commit Messages

- Use the present tense ("Add feature" not "Added feature")
- Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
- First line should be 50 characters or less
- Reference issues and pull requests where appropriate

## Project Structure

```
BAS/
├── docs/                 # Documentation
├── examples/             # Example implementations
├── src/                  # Source code
│   ├── core/             # Core functionality
│   ├── handshake/        # Handshake protocol
│   ├── keep_alive/       # Keep-alive system
│   ├── esperanto/        # AI-Esperanto implementation
│   ├── watchdog/         # Watchdog mechanisms
│   └── yellow_pages/     # AI Yellow Pages
├── tests/                # Test suite
└── tools/                # Development tools
```

## Development Workflow

1. **Issue Discussion**: Major changes should start with an issue for discussion
2. **Implementation**: Develop your feature or fix, with tests
3. **Code Review**: Submit PR for review
4. **Refinement**: Address feedback from maintainers
5. **Merge**: Once approved, a maintainer will merge your contribution

## Community

- Join our discussions on the GitHub [Discussions](https://github.com/mAiFriend/BAS/discussions) page
- Follow project updates through GitHub starring
- Share your implementations and ideas on the [wiki](https://github.com/mAiFriend/BAS/wiki)

Thank you for contributing to the BAS project!
