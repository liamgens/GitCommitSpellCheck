# Git Commit Spell Check

This is a simple Python script that acts as a git hook during the commit message stage. Simply add the script into your git hook folder inside your repository, and have your silly typing mistakes fixed for you.

### To Install

This script is dependent on the Python library [TextBlob](http://textblob.readthedocs.io/en/dev/index.html). To install TextBlob and the other necessary features, following the simple steps below.

1. Make sure you have Python 2.7 installed and set as the global path on your machine. You can check your Python version by running `python --version`.
2. Make sure you have pip (a Python package manager) installed on your machine as well. To install pip, follow the instructions [here](https://pip.pypa.io/en/stable/installing/).
3. Install TextBlob by running `pip install -U textblob` followed by running `python -m textblob.download_corpora`.
4. Once TextBlob is loaded, you can simply clone this repository and save the script titled `prepare-commit-message` into `.git/hooks/` in any git repository. Keep in mind this is client-side, so you will have to repeat this process for multiple machines if you wish to do so.