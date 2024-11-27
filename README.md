# {{cookiecutter.project_name}} MLOps_template

A flexible and customizable [Cookiecutter](https://cookiecutter.readthedocs.io/) template to kickstart Python projects with Poetry, pre-commit hooks, and a Makefile for automation.

## Features
- **Poetry** for dependency management
- **Pre-commit hooks** for maintaining code quality
- **Makefile** for easy project setup and common tasks
- Git repository initialization with `.gitignore`

## Usage
1. Install Cookiecutter:
   ```bash
   pip install cookiecutter

2. Generate a new project:

```bash
   cookiecutter gh:<your-username>/<repository-name>
```

3. Navigate to the project directory and initialize:

```bash
cd <your-project-name>
make -f Makefile.init initialize_all
```
Requirements:
- Python 3.11+
- Poetry
- Git
- Pre-commit
License
This project is licensed under the {{cookiecutter.license}} License.
