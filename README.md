<div align="center">

# Project Title
[![Python](https://img.shields.io/badge/Python-3776ab?logo=python&logoColor=white)](https://www.python.org/)
[![Code Quality](https://github.com/miguelbper/python-template/actions/workflows/code-quality.yaml/badge.svg)](https://github.com/miguelbper/python-template/actions/workflows/code-quality.yaml)
[![Unit Tests](https://github.com/miguelbper/python-template/actions/workflows/tests.yaml/badge.svg)](https://github.com/miguelbper/python-template/actions/workflows/tests.yaml)
[![codecov](https://codecov.io/gh/miguelbper/python-template/graph/badge.svg)](https://codecov.io/gh/miguelbper/python-template)
[![License](https://img.shields.io/badge/License-MIT-green.svg?labelColor=gray)](LICENSE)

*A brief description of what this project does and who it's for.*

![img.png](img.png)

</div>

---

## Description

*Provide a more detailed explanation about your project here. You can include:*
- *What problem does it solve?*
- *What technologies are used?*
- *What are the key features?*

## Features

- **Modern Python Tooling**: Uses `uv` for fast dependency management, `just` for command running, and `direnv` for environment management
- **Type Safety**: Configured with `pyright` for static type checking
- **Code Quality**: Uses `ruff` for linting and formatting
- **Testing**: Set up with `pytest` and coverage reporting
- **CI/CD**: GitHub Actions workflows for testing, code quality, and publishing
- **Version Management**: Automatic version management using git tags

## Tools Used

- **[uv](https://docs.astral.sh/uv/)**: A fast Python package installer and resolver
- **[just](https://github.com/casey/just)**: A command runner that makes it easy to run project-specific commands
- **[direnv](https://direnv.net/)**: Automatically loads and unloads environment variables based on the current directory
- **[pre-commit](https://pre-commit.com/)**: Git hooks to ensure code quality before commits
- **[ruff](https://docs.astral.sh/ruff/)**: A fast Python linter and formatter
- **[pyright](https://github.com/microsoft/pyright)**: Static type checker for Python
- **[pytest](https://docs.pytest.org/)**: Testing framework
- **[hatch](https://hatch.pypa.io/)**: Modern Python project manager

## Installation

*Provide installation instructions. Write out the commands the user should use to use your project.*

```bash
# Clone the repository
git clone https://github.com/username/project-name.git

# Navigate to the project directory
cd project-name

# Install dependencies
uv sync
```

## Project Structure

- `src/`: Source code directory
- `tests/`: Test files
- `.github/workflows/`: GitHub Actions workflows
- `justfile`: Project commands
- `pyproject.toml`: Project configuration
- `.envrc`: Environment variables (copy from .envrc.example)

## Available Commands

Use `just` to run project commands:

- `just setup`: Set up the development environment
- `just test`: Run tests
- `just test-cov`: Run tests with coverage
- `just pre-commit`: Run pre-commit hooks
- `just publish`: Create a new version tag

## Development Workflow

1. Set up environment variables in `.envrc`
2. Run `just setup` to initialize the project
3. Make changes and run tests with `just test`
4. Use `just publish` to create new versions

## Usage

*Explain how to use your project. Include code examples.*

```python
# Example code
def greet(name: str) -> str:
    return f"Hello, {name}!"

# Using the function
message = greet("World")
print(message)  # Output: Hello, World!
```

*You can also include screenshots or GIFs here to demonstrate usage.*

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- *List any resources, libraries, or tools that you used or were inspired by*
- *Credit any collaborators or contributors*
- *Link to any relevant documentation or articles*

## More badges

[![Bash](https://img.shields.io/badge/Bash-293036?logo=gnu-bash&logoColor=white)](https://www.gnu.org/software/bash/)
[![Git](https://img.shields.io/badge/Git-f44d27?logo=git&logoColor=white)](https://git-scm.com/)
[![NumPy](https://img.shields.io/badge/NumPy-4dabcf?logo=numpy&logoColor=white)](https://numpy.org/)
[![Pandas](https://img.shields.io/badge/Pandas-130654?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-5c7da2?logo=python&logoColor=white)](https://seaborn.pydata.org/)
[![SciPy](https://img.shields.io/badge/SciPy-013243?logo=scipy&logoColor=white)](https://scipy.org/)
[![SymPy](https://img.shields.io/badge/SymPy-3b5526?logo=sympy&logoColor=white)](https://www.sympy.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-f99f44?logo=scikitlearn&logoColor=white)](https://scikit-learn.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-ee4c2c?logo=pytorch&logoColor=white)](https://pytorch.org/)
[![PyTorch Lightning](https://img.shields.io/badge/-Lightning-7e4fff?logo=lightning&logoColor=white)](https://lightning.ai/docs/pytorch/stable/)
[![hydra](https://img.shields.io/badge/Configs-Hydra-89b8cd)](https://hydra.cc/)
[![Ruff](https://img.shields.io/badge/Ruff-261230?logo=ruff&logoColor=white)](https://github.com/astral-sh/ruff)
[![uv](https://img.shields.io/badge/uv-de5fe9?logo=uv&logoColor=white)](https://github.com/astral-sh/uv)
