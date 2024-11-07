# Movie Recomendation ...

> scikit, similarity, word2Vec, Python ENV & conda create

- Clone of : https://github.com/entbappy/Movie-Recommender-System-Using-Machine-Learning/

This is a Movie Recommender System built using Streamlit for the interface, pickle for loading pre-saved models, and requests to fetch movie poster images.

## Setup
- Run movie.ipynb in `jupyter notbook` ti generate artufacts
- Then activate env as well as `pip install -r requirements.txt`
- And run `streamlit run app.py`


## Files
```sh
PJ
	- READEME.md 
	- setup.py 
	- app.py
	- src/__init__.py 
	- requirements.txt
	- .gitignore
	- Procfile
	- setup.sh
# pip install urllib3==1.26.16
python3 -m venv env
source env/bin/activate
streamlit run app.py
```


__.gitignore__
```
# Byte-compiled / optimized / DLL files
__pycache__/
*.py[cod]
*$py.class

# C extensions
*.so

# Distribution / packaging
.Python
build/
develop-eggs/
dist/
downloads/
eggs/
.eggs/
lib/
lib64/
parts/
sdist/
var/
wheels/
pip-wheel-metadata/
share/python-wheels/
*.egg-info/
.installed.cfg
*.egg
MANIFEST

# PyInstaller
#  Usually these files are written by a python script from a template
#  before PyInstaller builds the exe, so as to inject date/other infos into it.
*.manifest
*.spec

# Installer logs
pip-log.txt
pip-delete-this-directory.txt

# Unit test / coverage reports
htmlcov/
.tox/
.nox/
.coverage
.coverage.*
.cache
nosetests.xml
coverage.xml
*.cover
*.py,cover
.hypothesis/
.pytest_cache/

# Translations
*.mo
*.pot

# Django stuff:
*.log
local_settings.py
db.sqlite3
db.sqlite3-journal

# Flask stuff:
instance/
.webassets-cache

# Scrapy stuff:
.scrapy

# Sphinx documentation
docs/_build/

# PyBuilder
target/

# Jupyter Notebook
.ipynb_checkpoints

# IPython
profile_default/
ipython_config.py

# pyenv
.python-version

# pipenv
#   According to pypa/pipenv#598, it is recommended to include Pipfile.lock in version control.
#   However, in case of collaboration, if having platform-specific dependencies or dependencies
#   having no cross-platform support, pipenv may install dependencies that don't work, or not
#   install all needed dependencies.
#Pipfile.lock

# PEP 582; used by e.g. github.com/David-OConnor/pyflow
__pypackages__/

# Celery stuff
celerybeat-schedule
celerybeat.pid

# SageMath parsed files
*.sage.py

# Environments
.env
.venv
env/
venv/
ENV/
env.bak/
venv.bak/

# Spyder project settings
.spyderproject
.spyproject

# Rope project settings
.ropeproject

# mkdocs documentation
/site

# mypy
.mypy_cache/
.dmypy.json
dmypy.json

# Pyre type checker
.pyre/

# if using pycharm
.idea

# if using VScode
.vscode

# add secret keys or API keys here
configs/secrets.yaml

# add your env folder here if its there
```