# Contributing to Inspiraspace

Thank you for your interest in contributing to Inspiraspace! We appreciate your time and effort in helping us create a vibrant online art marketplace. By following these guidelines, you can ensure a smooth and effective contribution process.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Getting Started](#getting-started)
- [Submitting Contributions](#submitting-contributions)
- [Conventional Commit Messages](#conventional-commit-messages)
- [Coding Guidelines](#coding-guidelines)
- [Testing](#testing)
- [Documentation](#documentation)
- [Review Process](#review-process)
- [Feedback and Support](#feedback-and-support)

## Code of Conduct

Before you start, please read and abide by our [Code of Conduct](CODE_OF_CONDUCT.md). We expect all contributors to create a respectful and inclusive environment within our community.

## Getting Started

1. **Fork the Repository:** Start by forking the repository you wish to contribute to.

2. **Clone Your Fork:** Clone your forked repository to your local machine.

    ```bash
    git clone https://github.com/your-username/repository-name.git
    ```

3. **Set Up Upstream:** Add the main Inspiraspace repository as an upstream remote.

    ```bash
    git remote add upstream https://github.com/inspiraspace/repository-name.git
    ```

4. **Sync with Upstream:** Regularly sync your fork with the latest changes from the upstream repository.

    ```bash
    git fetch upstream
    git checkout main
    git merge upstream/main
    ```

## Submitting Contributions

1. **Create a New Branch:** Before making changes, create a new branch for your contribution.

    ```bash
    git checkout -b feature/your-feature-name
    ```

2. **Make Changes:** Develop and test your changes in the new branch.

3. **Commit Your Changes:** Commit your changes with [conventional commit messages](#conventional-commit-messages).

    ```bash
    git add .
    git commit -m "feat: add new feature"
    ```

4. **Sync with Upstream:** Keep your branch updated with the latest upstream changes.

    ```bash
    git fetch upstream
    git merge upstream/main
    ```

5. **Push Your Changes:** Push your changes to your forked repository.

    ```bash
    git push origin feature/your-feature-name
    ```

6. **Submit a Pull Request:** Create a pull request from your branch to the main repository.

## Conventional Commit Messages

We follow the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) style for commit messages. Each commit message should have a structured format:

```
<type>(<scope>): <description>

[optional body]

[optional footer]
```

Examples of commit types include `feat`, `fix`, `chore`, `docs`, `style`, and more. Using this convention helps in generating changelogs and maintaining a consistent commit history.

## Coding Guidelines

- Follow the [JavaScript Style Guide](https://github.com/airbnb/javascript) by Airbnb for coding standards.
- Use descriptive variable and function names.
- Comment your code for clarity.

## Testing

- Write unit tests for your code.
- Ensure your code passes existing tests.
- Include new tests for new functionality or bug fixes.

## Documentation

- Document new features or changes you introduce.
- Update existing documentation if your contribution affects it.

## Review Process

- Your pull request will be reviewed by project maintainers.
- Expect feedback and possibly requests for changes.
- Address comments and make necessary adjustments.

## Feedback and Support

If you have questions or need assistance, feel free to:

- Open an issue on GitHub.
- Contact the project maintainers directly via email.

---

Thank you for contributing to Inspiraspace! Your efforts play a vital role in creating an exceptional online art marketplace for artists and enthusiasts alike.
