# Database programming: IB A3.3 SQL notebooks

Six Jupyter notebooks, one per syllabus statement. Each has an explanation, worked examples, TODO cells with automatic checks, and revision questions.

1. A3.3.1 SQL data language types
2. A3.3.2 Queries between two tables
3. A3.3.3 Updating data with SQL
4. A3.3.4 SQL aggregate functions
5. A3.3.5 Database views
6. A3.3.6 Transactions and ACID

## Run them in VS Code

1. Install the Python and Jupyter extensions.
2. Open a notebook, click **Select Kernel** (top right), choose a Python environment.
3. Run the first cell. It installs `jupysql` into the kernel if it is missing (about a minute, once).
4. Work down the notebook. Cells that print a tick or cross are checking your answer.

If `%%sql` fails, run `python3 -m pip install jupysql ipykernel`, restart the kernel, and run from the top.
