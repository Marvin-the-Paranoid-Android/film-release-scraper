# Film Release Scraper

## In VS Code, create project folder and navigate into it:  
mkdir film_release_scraper  
cd film_release_scraper  
  
## Initialise Git:  
git init  
  
## Create python virtual environment:  
python -m venv venv  
venv\Scripts\activate  # Only works for Windows, on macOS/Linux: source venv/bin/activate  
  
## Create an empty requirements.txt file:  
echo. > requirements.txt  
  
## Add the following to the requirements.txt file:  
requests  
beautifulsoup4  
pandas  
jupyter  
  
## Install the above python packages using:  
pip install -r requirements.txt  
  
## Create a git ignore file:  
echo.  > .gitignore  
  
## Add the below to this file:  
'''
\# Ignore virtual environment  
venv/  
  
\# Ignore Python bytecode  
\_\_pycache__/  
*.pyc  
  
\# Ignore Jupyter Notebook checkpoints  
.ipynb_checkpoints  
  
\# Ignore IDE folders  
.vscode/  
.idea/  
'''  

## Create basic project structure:  
echo. > scraper.ipynb  
echo. > README.md  
  
## Make the first commit:  
git add .  
git commit -m "Initial commit: Setup project structure"  