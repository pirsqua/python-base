Prerequisites
-------------
- VS Code
- Python
- Git


Setup
-----
1. In the terminal enter:
```
python -m venv .venv
.venv\Scripts\activate.bat
pip install -r requirements.txt
```

2. Double check your environment is set up correctly and using correct interpreter. Hit Ctrl-Shift-P and type `Python: Select Interpreter`. Then make sure it's using the one located under `.\.venv\Scripts\python.exe`.

3. Make sure you have installed the following VS Code Extensions: Python, Ruff, yapf, isort, and Python Indent.

4. Edit .vscode/launch.json to set files to debug. In the debug tab select a file and then hit F5.

5. Due to the settings in .vscode/settings.json, on save we run the linter (ruff), formatter, (yapf), and import organizer (isort). The formatting settings are contained in .style.yapf and pyproject.toml.
