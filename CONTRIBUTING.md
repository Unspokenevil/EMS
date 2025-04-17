# Contributing to EMS

Thank you for your interest in contributing to the Event Management System (EMS)! We welcome contributions from the community to improve the project. This document outlines the process for contributing, setting up your development environment, and submitting changes.

## How to Contribute

1. **Find an Issue:**
   - Browse open issues in the [GitHub Issues](https://github.com/VoxDroid/Event-Management-System/issues) page.
   - Look for issues labeled `good first issue` or `help wanted` for beginner-friendly tasks.
   - If you have an idea for a new feature or bug fix, open a new issue to discuss it.

2. **Fork the Repository:**
   - Fork the [EMS repository](https://github.com/VoxDroid/EMS) to your GitHub account.
   - Clone your fork to your local machine:
     ```bash
     git clone https://github.com/YOUR_USERNAME/EMS.git
     cd EMS
     ```

3. **Set Up Your Development Environment:**
   - Follow the [Installation](#installation) section in the [README.md](README.md) to set up the project.
   - Install additional development tools:
     - **PHPUnit** for PHP testing: `composer require --dev phpunit/phpunit`
     - **ESLint** for JavaScript linting: `npm install eslint --save-dev`
   - Configure pre-commit hooks (if available) to enforce coding standards.

4. **Create a Branch:**
   - Create a new branch for your feature or bug fix:
     ```bash
     git checkout -b feature/your-feature-name
     ```
   - Use descriptive branch names (e.g., `fix/login-bug`, `feature/calendar-export`).

5. **Make Changes:**
   - Follow the [Coding Standards](#coding-standards) below.
   - Write tests for new features or bug fixes.
   - Update documentation in `docs/` or `README.md` if your changes affect setup or usage.

6. **Test Your Changes:**
   - Run the test suite:
     ```bash
     vendor/bin/phpunit tests
     ```
   - Manually test the application in your browser to ensure functionality.
   - Verify that your changes do not break existing features.

7. **Commit Your Changes:**
   - Write clear, concise commit messages:
     ```bash
     git commit -m "Add feature: calendar export functionality"
     ```
   - Group related changes into logical commits.

8. **Push and Open a Pull Request:**
   - Push your branch to your fork:
     ```bash
     git push origin feature/your-feature-name
     ```
   - Open a pull request (PR) against the `main` branch of the [EMS repository](https://github.com/VoxDroid/EMS).
   - In the PR description, include:
     - A summary of your changes.
     - Reference to the related issue (e.g., `Fixes #123`).
     - Any additional context or screenshots (especially for UI changes).

9. **Respond to Feedback:**
   - Maintainers will review your PR and may request changes.
   - Address feedback promptly and push updates to the same branch.
   - Once approved, your changes will be merged!

## Coding Standards

- **PHP:**
  - Follow [PSR-12](https://www.php-fig.org/psr/psr-12/) coding standards.
  - Use meaningful variable and function names.
  - Add PHPDoc comments for functions and classes.
  - Avoid inline HTML in PHP files; use templates where possible.

- **JavaScript/CSS:**
  - Follow [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript).
  - Use SCSS for stylesheets and organize in `ASSETS/CSS/`.
  - Minify production assets using `npm run build`.

- **HTML:**
  - Write semantic HTML5.
  - Ensure accessibility (e.g., ARIA attributes, alt text for images).

- **Database:**
  - Use prepared statements for all database queries to prevent SQL injection.
  - Follow the existing schema in `database/schema.sql`.
  - Document any schema changes in `docs/database.md`.

- **Commits:**
  - Use the format: `[type]: Short description` (e.g., `feat: Add event filtering`, `fix: Resolve login redirect bug`).
  - Types: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`.

## Code of Conduct

All contributors are expected to adhere to the [Code of Conduct](CODE_OF_CONDUCT.md). Be respectful, inclusive, and professional in all interactions.

## Reporting Bugs

- Use the [GitHub Issues](https://github.com/VoxDroid/Event-Management-System/issues) page to report bugs.
- Provide a clear title, description, steps to reproduce, expected behavior, and actual behavior.
- Include screenshots or logs if applicable.

## Suggesting Features

- Open an issue with the label `enhancement`.
- Describe the feature, its use case, and potential implementation ideas.
- Discuss with maintainers before starting work to ensure alignment.

## Security Vulnerabilities

If you discover a security issue, please report it privately to [izeno.contact@gmail.com](mailto:izeno.contact@gmail.com). Do not disclose vulnerabilities publicly until they are resolved. See [SECURITY.md](SECURITY.md) for details.

## Questions?

Contact the project maintainer:

- **Email:** [izeno.contact@gmail.com](mailto:izeno.contact@gmail.com)
- **GitHub:** [@VoxDroid](https://github.com/VoxDroid)

Thank you for contributing to EMS! Your efforts help make this project better for everyone.