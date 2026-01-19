# Contributing

Contributions are welcome and will be fully credited.

## Bug Reports

If you discover a bug, please create an issue on GitHub with a clear title and detailed description. The more information you provide, the faster we can address the problem.

A good bug report includes:

- A clear, descriptive title
- Steps to reproduce the behavior
- Expected behavior vs actual behavior
- Your PHP and Laravel versions
- Any relevant code snippets or error messages

## Feature Requests

Feature requests are welcome. Please open an issue on GitHub and describe:

- The feature you would like to see
- Why you need it
- How it should work

Take a moment to consider whether your idea fits within the scope and aims of the project. It’s up to you to make a strong case for the merits of your feature.

## Pull Requests

Pull requests for bug fixes, improvements, and new features are a fantastic help. Please keep them focused in scope and avoid unrelated commits.

**Before submitting a pull request:**

1. Fork the repository and create your branch from `main`
1. If you’ve added code that should be tested, add tests
1. Ensure the test suite passes
1. Make sure your code follows the existing code style

**Pull request process:**

1. Update the README.md with details of changes if applicable
1. Update the CHANGELOG.md following the existing format
1. The PR will be merged once you have the sign-off of a maintainer

## Code Style

This project follows PSR-12 coding standards and uses [Laravel Pint](https://laravel.com/docs/pint) for code formatting.

Before submitting a PR, run Pint to ensure your code is properly formatted:

```bash
composer format
```

Or check without making changes:

```bash
composer format:test
```

## Running Tests

```bash
composer test
```

## Static Analysis

This project uses PHPStan for static analysis:

```bash
composer analyse
```

## Development Workflow

1. Clone your fork
1. Install dependencies: `composer install`
1. Create a feature branch: `git checkout -b feature/your-feature-name`
1. Make your changes and add tests
1. Run the full test suite: `composer test`
1. Commit your changes with a clear message
1. Push to your fork and submit a pull request

**Happy coding!**
