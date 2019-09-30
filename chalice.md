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

Make sure you have Python 3.6 installed. You can check this by running `python3 -v`.

### Creating a Python virtual environment

Every Python project needs its own virtual environment. Each virtual environment might use different versions of Python and different package so it's important to keep them separate. Instead of a `node_modules` folder, we will have a `venv` folder in the project (added to .gitignore). The `requirements.txt` file is similar to a `package.json`. When you clone a repo, you can run `pip3 install -r requirements.txt` instead of `npm install`.

`git clone`
`cd`
`python3 -m venv venv`
`pip install -r requirements.txt`
`source venv/bin/activate`

### Setting up AWS credentials


Install AWS Chalice as a dependency of our python project

`pip install chalice`

`chalice new-project our_app_name`
