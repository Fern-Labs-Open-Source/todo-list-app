# Contributing to the Todo List Application

Thank you for considering contributing to the Todo List application! This document provides guidelines and instructions for contributing to this project.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Getting Started](#getting-started)
- [Development Workflow](#development-workflow)
- [Pull Request Process](#pull-request-process)
- [Coding Standards](#coding-standards)
- [Testing](#testing)
- [Documentation](#documentation)

## Code of Conduct

Please read and follow our [Code of Conduct](./CODE_OF_CONDUCT.md). By participating in this project, you agree to abide by its terms.

## Getting Started

1. Fork the repository
2. Clone your forked repository: `git clone https://github.com/your-username/todo-list-app.git`
3. Add the original repository as upstream: `git remote add upstream https://github.com/Fern-Labs-Open-Source/todo-list-app.git`
4. Create a new branch for your feature or bug fix: `git checkout -b feature/your-feature-name`
5. Make your changes
6. Push to your fork: `git push origin feature/your-feature-name`
7. Create a Pull Request against the main branch of the original repository

## Development Workflow

Our development workflow emphasizes quality and simplicity:

1. **Focus on MVP First**: Prioritize completing core features with high quality
2. **Quality Over Quantity**: We prefer fewer well-implemented features over many partial implementations
3. **Test-Driven Approach**: Write tests alongside your code to prevent regressions
4. **Iterative Development**: Seek feedback early and adapt accordingly

## Pull Request Process

1. **Branch Naming**: Use the following naming convention:
   - `feature/short-description` for new features
   - `fix/issue-description` for bug fixes
   - `refactor/component-name` for code refactoring
   - `docs/description` for documentation updates

2. **Commit Messages**: Follow conventional commits format:
   - Format: `type(scope): description`
   - Example: `feat(tasks): add recurring task functionality`
   - Types: feat, fix, docs, style, refactor, test, chore

3. **Pull Request Content**:
   - Provide a clear description of the changes
   - Reference any related issues
   - Include screenshots for UI changes
   - Describe any new dependencies
   - Update documentation if needed

4. **Code Review**:
   - Address all review comments
   - Request re-review when changes are made
   - Be open to constructive feedback

5. **Merge Requirements**:
   - All automated checks must pass
   - Changes should be tested thoroughly
   - Code should adhere to project standards

## Coding Standards

Please follow the coding standards outlined in our [Development Guide](./development.md):

- Use TypeScript for type safety
- Follow ESLint and Prettier configurations
- Write self-documenting code with clear names
- Keep functions small and focused
- Follow component-based architecture
- Use async/await for asynchronous code

## Testing

We prioritize automated testing to prevent regressions:

- Write tests alongside code implementation
- Test behavior, not implementation details
- Focus on critical user journeys
- Make tests deterministic and repeatable
- Use appropriate test types for different scenarios:
  - Unit tests for individual functions and components
  - Integration tests for component interactions
  - End-to-end tests for critical user flows

## Documentation

Good documentation is essential:

- Update README.md with any necessary changes
- Document new features in appropriate documentation files
- Add JSDoc comments to public API methods
- Include inline comments for complex logic
- Keep documentation up-to-date with code changes

---

Thank you for contributing to make the Todo List application better!