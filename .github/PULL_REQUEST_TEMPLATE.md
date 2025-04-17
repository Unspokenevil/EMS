# Pull Request Template

Thank you for contributing to the Event Management System (EMS)! Please fill out the sections below to help us review your pull request efficiently. Ensure your changes align with the [CONTRIBUTING.md](CONTRIBUTING.md) guidelines and the [Code of Conduct](CODE_OF_CONDUCT.md).

## Description

Provide a clear and concise description of the changes or features you've implemented. Explain the purpose of this pull request and what problem it solves.

- **What does this PR do?**
- **Why is this change needed?**
- **Related issue (if applicable):** Link to the issue (e.g., `Fixes #123`)

## Type of Change

Check the applicable boxes:

- [ ] Bug fix (non-breaking change that fixes an issue)
- [ ] New feature (non-breaking change that adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] Documentation update
- [ ] Refactoring (code improvements without changing functionality)
- [ ] Other (please specify):

## How Has This Been Tested?

Describe how you tested your changes to ensure they work as expected.

- **Automated Tests:** Did you add or update unit tests? (e.g., `vendor/bin/phpunit tests`)
- **Manual Tests:** What steps did you perform to verify the changes? (e.g., "Tested event creation in the web interface")
- **Browsers Tested:** List browsers used for testing (e.g., Chrome, Firefox)
- **Environment:** Specify the environment (e.g., PHP 8.0, MySQL 5.7, Apache)

## Screenshots (if applicable)

If your changes affect the UI, please attach screenshots or GIFs to demonstrate the changes. For example, include before-and-after images for visual updates.

## Checklist

Ensure your pull request meets the following requirements:

- [ ] My code follows the [PSR-12](https://www.php-fig.org/psr/psr-12/) coding standards for PHP and the [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript) for JavaScript.
- [ ] I have updated or added relevant documentation in `docs/` or `README.md`.
- [ ] I have added tests that cover my changes, or existing tests are sufficient.
- [ ] All new and existing tests pass (`vendor/bin/phpunit tests`).
- [ ] My changes do not introduce new warnings or errors (e.g., linting errors).
- [ ] I have checked for conflicts with the `main` branch.
- [ ] My commit messages follow the format: `[type]: Short description` (e.g., `feat: Add event filtering`).

## Additional Notes

Add any extra information that might help reviewers understand your changes, such as:

- Challenges faced during implementation.
- Future improvements planned for this feature.
- Dependencies introduced (if any).

## Security Considerations

If your changes involve security-related updates (e.g., authentication, database queries):

- [ ] I have used prepared statements for all database queries to prevent SQL injection.
- [ ] I have followed security best practices outlined in [SECURITY.md](SECURITY.md).
- [ ] I have not exposed sensitive information (e.g., credentials, API keys).

If this PR addresses a security vulnerability, please contact [izeno.contact@gmail.com](mailto:izeno.contact@gmail.com) privately instead of including details here.

## Reviewer Instructions

For maintainers (@VoxDroid and others):

- Review the code for adherence to coding standards.
- Verify that tests pass and cover the changes.
- Test the changes locally if they involve UI or complex logic.
- Provide constructive feedback within 7 days of the PR submission.

## Contact

For questions about this pull request, reach out to:

- **GitHub:** [@VoxDroid](https://github.com/VoxDroid)
- **Email:** [izeno.contact@gmail.com](mailto:izeno.contact@gmail.com)

Thank you for your contribution to EMS!