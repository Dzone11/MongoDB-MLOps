# MONGODB - MLOPs

# Project Documentation

## requirements_dev.txt

`requirements_dev.txt` is used for testing purposes. It simplifies the installation and management of dependencies specifically for development and testing, keeping them separate from the dependencies required for production.

## Difference between requirements.txt and requirements_dev.txt

`requirements.txt` specifies the dependencies for running the production code of a Python project, while `requirements_dev.txt` specifies dependencies for development and testing.

## tox.ini

We use `tox.ini` for testing Python packages against different Python versions. `tox` works by creating environments, installing dependencies, and running specified commands. It acts as a combination of `virtualenvwrapper` and `makefile`, creating a `.tox` directory.

## pyproject.toml

`pyproject.toml` is used for configuring Python projects and serves as an alternative to `setup.cfg`. It contains information related to the build system, such as the build tool used, package name, version, author, license, and dependencies.

## setup.cfg

In summary, `setup.cfg` is used by setuptools to configure the packaging and installation of a Python project.

## Testing Python Applications

### Types of Testing

- **Automated Testing**
- **Manual Testing**

### Modes of Testing

- **Unit Testing**
- **Integration Testing**

### Testing Frameworks

- **pytest**
- **unittest**
- **robotframework**
- **selenium**
- **behave**
- **doctest**

### Code Style and Syntax Checking

- **pylint**
- **flake8** (includes `pylint`, `pycodestyle`, and `mccabe`)
