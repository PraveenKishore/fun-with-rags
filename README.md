## Fun with RAGs

This project uses [uv](https://docs.astral.sh/uv/) to manage dependencies.

Open [Presentation.ipynb](/Presentation.ipynb) jupyter notebook in local for a RAG walkthrough.

## Setup
This project uses [uv](https://docs.astral.sh/uv/) for package/project management. 
To run this project, follow the below setup instructions.

1. Install uv if you haven't already. [Here's](https://docs.astral.sh/uv/getting-started/installation/) the installation instructions.
2. Clone the repo.
   ```sh
   git clone https://github.com/PraveenKishore/fun-with-rags.git
   cd fun-with-rags
   ```
3. Create virtual env and install dependencies.
   ```sh
   uv sync
   ```
4. Activate the virtual env.
   ```sh
   source .venv/bin/activate  # Activate the virtual environment (Linux/MacOS)
   # OR
   .\.venv\Scripts\activate  # Activate the virtual environment (Windows)
   ```
5. You're all set!