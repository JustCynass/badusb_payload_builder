# Contributing to Bad USB - Payload Builder

Thank you for considering contributing to the PyExe Builder Professional project! We welcome contributions from the community to help improve this open-source GUI application for converting Python scripts into standalone executables. This guide outlines how you can contribute effectively.

## Code of Conduct

Please review our [Code of Conduct](CODE_OF_CONDUCT.md) to understand the expectations for all contributors and maintain a welcoming environment.

## How to Contribute

### Reporting Bugs
- Check the [Issues page](https://github.com/justcynass/badusb_payloadbuilder/issues) to ensure the bug hasn't already been reported.
- Open a new issue with a clear title and description, including steps to reproduce, expected behavior, and actual behavior.
- Use the bug report template if available.

### Suggesting Features
- Check the [Issues page](https://github.com/justcynass/badusb_payloadbuilder/issues) to see if the feature has been proposed.
- Open a new issue with a clear title and detailed description of the feature, including its purpose and potential implementation.
- Use the feature request template if available.

### Submitting Code Changes
1. **Fork the Repository**:
   - Fork the repository at [https://github.com/justcynass/badusb_payloadbuilder](https://github.com/justcynass/badusb_payloadbuilder).
2. **Clone Your Fork**:
   ```bash
   git clone https://github.com/<your-username>/BadUSB_PayloadBuilder
   ```
3. **Create a Feature Branch**:
   ```bash
   git checkout -b feature/your-feature-name
   ```
4. **Make Changes**:
   - Follow the coding style and conventions used in the project (e.g., PEP 8 for Python, consistent formatting).
   - Ensure your changes are well-documented and include tests if applicable.
   - Update `app.py` or other relevant files as needed, maintaining the existing structure.
5. **Commit Changes**:
   - Use clear, descriptive commit messages.
   ```bash
   git commit -m "Add your descriptive message here"
   ```
6. **Push to Your Fork**:
   ```bash
   git push origin feature/your-feature-name
   ```
7. **Open a Pull Request**:
   - Go to the original repository and create a pull request from your branch.
   - Use the [Pull Request Template](PULL_REQUEST_TEMPLATE.md) to provide details about your changes.
   - Reference any related issues (e.g., `Fixes #123`).

### Setting Up the Development Environment
- Follow the [Installation](#installation) section in the [README.md](README.md) to set up the project locally.
- Ensure you have Python 3.8+ and pip installed.
- Run `python start.py` to create a virtual environment and install dependencies (`PyQt6`, `psutil`, `pyinstaller`, `qtawesome`).
- Test your changes by launching the GUI with `python start.py`.

## Guidelines
- **Code Quality**: Ensure your code is clean, readable, and follows PEP 8 standards.
- **Testing**: Test changes locally to ensure the GUI functions correctly across supported platforms (Windows, Linux, macOS).
- **Documentation**: Update the `README.md` or inline comments if your changes affect usage or setup.
- **Security**: If you identify a security vulnerability, please follow our [Security Policy](SECURITY.md).

## Review Process
- Pull requests will be reviewed by maintainers as soon as possible.
- Expect feedback or requests for changes to ensure quality and consistency.
- Once approved, your changes will be merged into the main branch.

## Questions?
If you have questions or need help, feel free to:
- Open an issue on the [Issues page](https://github.com/justcynass/badusb_payloadbuilder/issues).
- Contact the maintainer at [@Cynass](https://github.com/justcynass).

Thank you for contributing to PyExe Builder Professional!
