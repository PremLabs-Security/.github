# Contributing to PremLabs-Security

We welcome and appreciate contributions from the community to help us advance AI Security Research and build open-source cybersecurity tools. By contributing, you agree to abide by our Code of Conduct.

## How to Contribute

### 1. Find an Issue or Feature

- Browse our repositories to find open issues or suggest new features.
- If you plan to add a new feature or make a significant change, please open an issue first to discuss it.

### 2. Fork the Repository

- Fork the repository you wish to contribute to.
- Clone your forked repository to your local machine:
  ```bash
  git clone https://github.com/your-username/repository-name.git
  cd repository-name
  ```

### 3. Create a New Branch

- Create a new branch for your feature or bug fix:
  ```bash
  git checkout -b feature/your-feature-name
  # or
  git checkout -b bugfix/issue-description
  ```

### 4. Make Your Changes

- Ensure your code adheres to the project's coding standards (e.g., Python 3.10+, type hints, well-commented code).
- Write clear, concise, and well-documented code.
- Add or update tests to cover your changes.

### 5. Test Your Changes

- Run existing tests and ensure they pass.
- If you added new features, ensure your new tests pass.

### 6. Commit Your Changes

- Write clear and descriptive commit messages.
  ```bash
  git commit -m "feat: Add new feature for X"
  # or
  git commit -m "fix: Resolve bug in Y"
  ```

### 7. Push to Your Fork

```bash
git push origin feature/your-feature-name
```

### 8. Create a Pull Request (PR)

- Go to the original repository on GitHub and open a new Pull Request.
- Provide a detailed description of your changes, why they are necessary, and any relevant issue numbers.
- Ensure your PR passes all CI/CD checks.

## Code Requirements

- **Python 3.10+**: All Python code must be compatible with Python 3.10 or newer.
- **Well-commented, production-ready code**: Code should be easy to understand and maintain.
- **Type hints**: Use type hints for all function arguments and return values.
- **Async where needed**: Utilize `asyncio` for I/O-bound operations to improve performance.
- **Ethical use disclaimer**: All tools must include a clear disclaimer regarding ethical use.
- **MIT License**: All new projects and significant contributions will be under the MIT License, attributed to "Pramod Jogdand / PremLabs-Security".

## Code of Conduct

We are committed to fostering an open and welcoming environment. Please read and follow our [Code of Conduct](CODE_OF_CONDUCT.md) (to be created) in all interactions.

Thank you for contributing to PremLabs-Security!
