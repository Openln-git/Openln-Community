# Contributing to Openln

Thank you for your interest in contributing to Openln! This document provides guidelines and information on how to contribute effectively to our projects.

## Code of Conduct

By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md). Please read it before contributing.

## How to Contribute

### 🐛 Reporting Bugs

- Use GitHub Issues to report bugs
- Check existing issues to avoid duplicates
- Provide clear, detailed bug reports with:
  - Steps to reproduce
  - Expected behavior
  - Actual behavior
  - Environment details
  - Screenshots/logs when applicable

### 💡 Suggesting Features

- Submit feature requests via GitHub Issues
- For major features, consider submitting an RFC (see [RFC Process](RFC/))
- Clearly describe:
  - The problem your feature solves
  - Your proposed solution
  - Alternative solutions considered
  - Implementation considerations

### 🔧 Code Contributions

#### Getting Started

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature-name`
3. Make your changes
4. Test your changes thoroughly
5. Commit with clear, descriptive messages
6. Push to your fork
7. Submit a pull request

#### Pull Request Guidelines

- **Keep PRs focused**: One feature or fix per PR
- **Write clear descriptions**: Explain what changes you made and why
- **Include tests**: Add or update tests for new functionality
- **Follow coding standards**: Maintain consistency with existing code
- **Update documentation**: Update relevant docs for your changes
- **Reference issues**: Link to related issues using keywords (e.g., "Fixes #123")

#### Commit Message Format

```
type(scope): brief description

Detailed explanation if needed.

Fixes #issue-number
```

Types: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`

### 📚 Documentation

- Help improve documentation clarity and completeness
- Fix typos, broken links, or outdated information
- Add examples and tutorials
- Translate documentation (if applicable)

### 🤝 Community Support

- Help answer questions in discussions
- Review pull requests
- Participate in community discussions
- Mentor new contributors

## Development Workflow

### Current Focus: openln-engine MVP

Our current priority is developing the openln-engine MVP. See our [roadmap](ROADMAP.md) for specific areas where contributions are needed.

### Setting Up Development Environment

1. Fork and clone the repository
2. Follow project-specific setup instructions in each repository's README
3. Install dependencies
4. Run tests to ensure everything works

### Testing

- Write tests for new features and bug fixes
- Ensure all existing tests pass
- Test across different environments when applicable
- Include integration tests for complex features

### Code Review Process

1. Submit your pull request
2. Automated checks will run (when configured)
3. Community members will review your changes
4. Address feedback and iterate
5. Once approved, maintainers will merge your PR

## RFC Process

For significant changes, feature proposals, or architectural decisions, use our RFC (Request for Comments) process. See [RFC/README.md](RFC/README.md) for details.

## Release Process

- We follow semantic versioning (SemVer)
- Releases are managed by maintainers
- Release notes document changes and migration guides

## Getting Help

- **Questions**: Use GitHub Discussions
- **Issues**: Use GitHub Issues for bugs and feature requests
- **Chat**: Join our community chat (links in main README)
- **RFCs**: Submit formal proposals for major changes

## Recognition

We value all contributions! Contributors will be:
- Listed in project contributors
- Acknowledged in release notes for significant contributions
- Invited to join the contributor community

## Development Guidelines

### Code Quality

- Write clean, readable, maintainable code
- Follow existing patterns and conventions
- Add comments for complex logic
- Keep functions and files focused and reasonably sized

### Performance

- Consider performance implications of changes
- Profile code when making performance-critical changes
- Avoid premature optimization

### Security

- Follow security best practices
- Report security vulnerabilities privately
- Don't commit sensitive information

### Compatibility

- Maintain backward compatibility when possible
- Document breaking changes clearly
- Provide migration guides for breaking changes

## License

By contributing to Openln, you agree that your contributions will be licensed under the same license as the project.

---

Thank you for contributing to Openln! Together, we're building something amazing. 🚀