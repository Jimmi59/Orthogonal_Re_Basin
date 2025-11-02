# Orthogonal Re-Basin: Beyond Permutations in Model Merging

This project uses [uv](https://github.com/astral-sh/uv) for high-performance Python environment and package management.

## Setup Instructions

Follow these steps to create a local development environment.

### 1. Prerequisites

Ensure you have `uv` installed. If not, you can install it globally using `pip`:

```bash
pip install uv
```

### 2. Create the Virtual Environment

From the root of this project directory, create a virtual environment (this will create a .venv folder):

```Bash
uv venv
```
### 3. Activate the Environment

You must activate the environment in your shell session:

On macOS / Linux (bash/zsh):

```Bash
source .venv/bin/activate
```

On Windows (PowerShell):

```Bash
.venv\Scripts\Activate.ps1
```

On Windows (CMD):

```Bash
.venv\Scripts\activate.bat
```
(You will see a (.venv) prefix in your terminal prompt once it's active.)

### 4. Install Dependencies

With the environment active, install all required packages from requirements.txt:

```Bash
uv pip install -r requirements.txt
```
