# Contributing to RevProxy

First off, thank you for considering contributing to RevProxy. It's people like you that make RevProxy such a great tool.

## How Can I Contribute?

### Reporting Bugs

This section should guide the user on how to report a bug.

- **Ensure the bug was not already reported** by searching on GitHub under [Issues](https://github.com/your-repo/issues).
- If you're unable to find an open issue addressing the problem, [open a new one](https://github.com/your-repo/issues/new). Be sure to include a **title and clear description**, as much relevant information as possible, and a **code sample** or an **executable test case** demonstrating the expected behavior that is not occurring.

### Suggesting Enhancements

This section should guide the user on how to suggest an enhancement.

- Open a new issue and provide a clear and detailed explanation of the feature you're suggesting.
- Explain why this enhancement would be useful to other users.

### Development Workflow

1.  Fork the repository on GitHub.
2.  Clone your forked repository to your local machine.
3.  Create a new branch for your changes. Please follow the branch naming conventions below.
4.  Make your changes, and commit them with clear and descriptive commit messages.
5.  Push your changes to your forked repository.
6.  Open a pull request from your branch to the `main` branch of the original repository.
7.  Work with the maintainers to address any feedback and get your pull request merged.

### Pull Request Process

1.  Ensure your code is well-tested and that all existing and new tests pass.
2.  Update the README.md with details of changes to the interface, this includes new environment variables, exposed ports, useful file locations and container parameters.
3.  Increase the version numbers in any examples files and the README.md to the new version that this Pull Request would represent. The versioning scheme we use is [SemVer](http://semver.org/).
4.  You may merge the Pull Request in once you have the sign-off of two other developers, or if you do not have permission to do that, you may request the second reviewer to merge it for you.

## Styleguides

### Git Commit Messages

- Use the present tense ("Add feature" not "Added feature").
- Use the imperative mood ("Move cursor to..." not "Moves cursor to...").
- Limit the first line to 72 characters or less.
- Reference issues and pull requests liberally after the first line.

### Branch Naming

Please follow this convention for your branch names: `username/type/short-description`

- **feat**: A new feature (e.g., `mikiasgoitom/feat/add-prometheus-metrics`)
- **fix**: A bug fix (e.g., `mikiasgoitom/fix/handle-nil-pointer`)
- **docs**: Documentation only changes (e.g., `mikiasgoitom/docs/update-contributing-guide`)
- **style**: Changes that do not affect the meaning of the code (white-space, formatting, etc)
- **refactor**: A code change that neither fixes a bug nor adds a feature
- **test**: Adding missing tests or correcting existing tests
- **chore**: Changes to the build process or auxiliary tools and libraries

### Code Styleguide

- Follow the standard Go coding style. Run `go fmt` on your code before committing.
- Write clear and concise comments where necessary.
- Ensure your code is well-tested. You can run tests using the `task test` command.
- Run `go vet` to catch any potential issues.
