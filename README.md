# ARI5102 - Data Analysis Techniques Assignment

Code repository for the University of Malta (UOM) ARI5102 (Data Analysis Techniques) study-unit assignment.

**Contact**: [Michael Vella](michael.vella.20@um.edu.mt).

## Project notes:

- **Python version used**: 3.12.3.
- **Packages used**: Refer to packages inside `requirements.txt`.

## Replication of virtual environment (.venv)

Assuming that Python is already pre-installed on the host machine and the repository is already cloned locally.

1. Run `python -m venv .venv` to create the Python virtual environment. `python` here refers to the alias of the Python executable path and depends on the alias used on the host machine (full Python path can also be used). Running this command will create a Python virtual environment depending on the base Python version being used to create the environment.
2. Activate virtual environment by running `.venv\Scripts\activate` (Windows) or `source .venv/bin/activate` (Mac/Linux).
3. Upgrade `pip` (Python's package manager) by running `pip install --upgrade pip`.
4. Run `pip install -r requirements.txt` to download any packages required for this project.

Your local setup is finished and you can now run the code.
