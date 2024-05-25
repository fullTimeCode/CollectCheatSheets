# Poetry Cheatsheet

To start a new Python project using Poetry and structure the app, follow these steps:

## Create a New Project with Poetry

1. **Install Poetry**: If you haven't already, install Poetry by running the command `curl -sSL https://install.python-poetry.org | python3 -` in your terminal.
2. **Create a new Poetry project**: Run the command `poetry new my_project` to create a new Poetry project called "my_project". This will create a directory with the project name and populate it with basic scaffolding for a project, including a `pyproject.toml` file, a `README.md` file, and subdirectories for tests and project code.
3. **Navigate into the project directory**: Use the command `cd my_project` to navigate into the newly created project directory.

### Configure Project Dependencies

1. **Add dependencies**: Use the command `poetry add <dependency_name>` to add dependencies to your project. For example, `poetry add requests` to add the `requests` library.
2. **Install dependencies**: Run `poetry install` to install the dependencies specified in your `pyproject.toml` file. This command will create a virtual environment for your project and install the dependencies within it.

## Structure the App

The project structure created by Poetry includes the following files and directories:

- `pyproject.toml`: This file contains the project's metadata and configuration.
- `README.md`: This file contains information about your project.
- `my_project`: This folder contains the source code files for your project.
- `tests`: This folder contains the test files for your project.

## Running the App

To run your script, use the command `poetry run python your_script.py`. This will run your script within the virtual environment created by Poetry.

## Publishing to PyPI

Once your project is ready, you can publish it to PyPI (Python Package Index) using Poetry. This allows other developers to easily install and use your package.

Remember to replace "my_project" with your actual project name throughout the process.
