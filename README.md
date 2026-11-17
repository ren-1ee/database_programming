# Database programming: IB A3.3 SQL notebooks

Six Jupyter notebooks, one per syllabus statement. Each has an explanation, worked examples, TODO cells with automatic checks, and revision questions.

1. A3.3.1 SQL data language types
2. A3.3.2 Queries between two tables
3. A3.3.3 Updating data with SQL
4. A3.3.4 SQL aggregate functions
5. A3.3.5 Database views
6. A3.3.6 Transactions and ACID

## One-time setup (Mac, VS Code)

1. Install the **Python** and **Jupyter** extensions in VS Code.
2. Put the notebooks in a folder and open that folder in VS Code (File > Open Folder).
3. Open a terminal in VS Code (Terminal > New Terminal) and run these three commands, one at a time:

```bash
python3 -m venv .venv
```

```bash
source .venv/bin/activate
```

```bash
python -m pip install --upgrade pip ipykernel jupysql
```

4. Open a notebook. Click **Select Kernel** (top right), choose **Python Environments**, then pick the one that ends in `.venv/bin/python`.
5. Click **Run All**, or run cells one at a time. Cells that print a tick or a cross are checking your answer.

## If something goes wrong

- **"requires the ipykernel package"**: you picked the wrong Python. Click **Change Kernel** and choose the `.venv` one. Do not click Install on a different Python.
- **Kernel not listed**: press Cmd+Shift+P, run **Developer: Reload Window**, then try Select Kernel again.
- **`%%sql` fails**: in the terminal run `python -m pip install jupysql ipykernel` (with `(.venv)` showing in the prompt), then click **Restart** and run from the top.
- **Python version**: use the Python that macOS provides, or a normal release from python.org (3.9 to 3.13). Avoid pre-release or very new versions (for example 3.16): some packages do not support them yet.
