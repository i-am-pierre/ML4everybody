# ML For Everybody

Repository for me to use when learning about ML from [freeCodeCamp.org](https://www.youtube.com/watch?v=i_LwzRVP7bg). Code is being updated and tested on Apple Silicon, using Python 3.11.9.

Full acknowledgments, thanks and credit to [Kylie Ying](https://www.youtube.com/c/YCubed) / [@kying18](https://github.com/kying18) for sharing here knowledge.

## Prerequisites

- Python 3.11.9 (3.12 not fully compatible with scikit-learn)
- pip
- Jupyter Notebook
- Dataset from UC Irvine:
  - [MAGIC Gamma Telescope](https://archive.ics.uci.edu/dataset/159/magic+gamma+telescope)
  - [Seoul Bike Sharing Demand](https://archive.ics.uci.edu/dataset/560/seoul+bike+sharing+demand)
  - [Seeds](https://archive.ics.uci.edu/dataset/236/seeds)

## Setting up the Project

1. **Create a Virtual Environment**: Create a new virtual environment for the project. The command to do this varies depending on your operating system:

   - On Unix or macOS: `python3 -m venv .venv`
   - On Windows: `python -m venv .venv`

   Here, `.venv` is the name of the virtual environment.

2. **Activate the Virtual Environment**: Activate the virtual environment. The command to do this also varies depending on your operating system:

   - On Unix or macOS: `source .venv/bin/activate`
   - On Windows: `.venv\Scripts\activate`

   You should see `(.venv)` in your terminal prompt, indicating that the virtual environment is active.

3. **Install the Requirements**: Install the packages from the `requirements.txt` file using the command `pip install -r requirements.txt`.

## Additional Notes

- The `.gitignore` file in the project folder includes the virtual environment and other unnecessary files and folders.
- The `requirements.txt` file in the project folder lists all the dependencies that the project needs.
- The `.vscode` folder in the project folder includes the settings and configurations for Visual Studio Code.
