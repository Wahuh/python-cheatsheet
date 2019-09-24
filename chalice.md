## Getting Started

### Seting up your environment

Watch this first:

https://www.youtube.com/watch?v=Kg1Yvry_Ydk

Python 3.5 or higher needs to specify `pip3`

- `requirements.txt` - similar to `package.json`
- `venv` folder - similar to `node_modules`, add it to `.gitignore` so you don't commit it
- `pip list` - check which packages are installed
- `pip freeze > requirements.txt` - similar to `npm init`, creates a `requirements.txt` file based on what packages are installed in your virtual environment (venv)
- `deactivate` - deactivate a virtual environment
- `python3 -m venv my_project/venv` - create a virtual environment
- `source my_project/venv/bin/activate` - activate a virtual environment
- `pip install -r requirements.txt` - similar to `npm install`, uses your requirements.txt to install all the packages

### Installation

Install AWS Chalice as a dependency of our python project

`pip install chalice`

`chalice new-project our_app_name`
