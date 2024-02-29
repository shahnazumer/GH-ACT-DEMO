Summary

1. Build:

This stage installs the required Python version.
It then installs dependencies from the requirements.txt file using pip.

2. Lint:

This stage installs Flake8, a Python linting tool.
It then runs Flake8 on your Python files to check for linting errors.

3. Test:
This stage also installs the required Python version and dependencies.
It starts the Flask server in testing mode.
It runs your Pytest tests for the Flask application.


Now, whenever you push new code or create a pull request to the main branch, this pipeline will run automatically. Each stage will execute in order, and you can check the Actions tab in your GitHub repository to see the pipeline runs and any potential errors in your linting or tests.