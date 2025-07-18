
# My Jupyter Notebooks

This is a collection of my jupyter notebooks for testing.

## Setup Instructions

This project uses Python 3.13.5 and a virtual environment for dependency management.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/madittman/jupyter_notebooks.git
    ```

2.  **Create and activate the virtual environment:**
    ```bash
    python3.13 -m venv .venv
    source .venv/bin/activate  # On Linux/macOS
    ```

3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    python -m ipykernel install --user --name=.venv --display-name="Python (.venv)"  # Create kernel spec
    ```

4.  **Run a jupyter notebook:**
    ```bash
    jupyter notebook <filename>.ipynb
    ```

5.  **Deactivate the virtual environment (when done):**
    ```bash
    deactivate
    ```

