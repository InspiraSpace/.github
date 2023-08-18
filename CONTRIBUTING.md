# Contribution Guidelines

Thank you for considering contributing to the Inspiraspace project! We welcome your input and collaboration to make this online art marketplace even better. By following these guidelines, you can help us maintain a consistent and productive contribution process.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Getting Started](#getting-started)
- [Submitting Contributions](#submitting-contributions)
- [Coding Guidelines](#coding-guidelines)
- [Testing](#testing)
- [Documentation](#documentation)
- [Review Process](#review-process)
- [Feedback and Support](#feedback-and-support)

## Code of Conduct

Please review and abide by our [Code of Conduct](CODE_OF_CONDUCT.md) to ensure a welcoming and respectful environment for all contributors.

## Getting Started

1. **Fork the Repository:** Start by forking the main Inspiraspace repository to your GitHub account.

2. **Clone Your Fork:** Clone your forked repository to your local development environment.

    ```bash
    git clone https://github.com/your-username/inspiraspace.git
    ```

3. **Set Up the Upstream Remote:** Add the original Inspiraspace repository as an upstream remote.

    ```bash
    git remote add upstream https://github.com/inspiraspace/inspiraspace.git
    ```

4. **Sync with Upstream:** Regularly sync your fork with the upstream repository to keep it up-to-date.

    ```bash
    git fetch upstream
    git checkout main
    git merge upstream/main
    ```

## Submitting Contributions

1. **Create a New Branch:** Before making any changes, create a new branch for your contribution.

    ```bash
    git checkout -b feature/your-feature-name
    ```

2. **Make Changes:** Develop and test your changes in the new branch.

3. **Commit Your Changes:** Commit your changes with clear and concise commit messages.

    ```bash
    git add .
    git commit -m "Add a descriptive commit message"
    ```

4. **Sync with Upstream:** Before submitting a pull request, make sure your branch is synced with the latest upstream changes.

    ```bash
    git fetch upstream
    git merge upstream/main
    ```

5. **Push Your Changes:** Push your changes to your forked repository.

    ```bash
    git push origin feature/your-feature-name
    ```

6. **Submit a Pull Request:** Create a pull request from your branch to the `main` branch of the main Inspiraspace repository.

## Coding Guidelines

- Follow the [JavaScript Style Guide](https://github.com/airbnb/javascript) by Airbnb for coding standards.
- Write clear, meaningful variable and function names.
- Comment your code to explain complex sections, assumptions, or reasons for specific approaches.

## Testing

- Write unit tests for your code.
- Ensure your code passes all existing tests.
- Include new tests to cover new functionality or bug fixes.

## Documentation

- Document any new features or changes you introduce.
- Update existing documentation if your contribution affects it.

## Review Process

- Pull requests will be reviewed by project maintainers.
- Expect feedback, suggestions, and possibly requests for changes.
- Address comments and make necessary adjustments to your code.

## Feedback and Support

If you have questions, need assistance, or want to discuss your contribution, feel free to:

- Open an issue on GitHub.
- Join our community chat (link available in the README).
- Contact the project maintainers directly via email.

---

Thank you for your interest in contributing to Inspiraspace. Your contributions make a difference in creating a vibrant online art marketplace for artists and art enthusiasts!
