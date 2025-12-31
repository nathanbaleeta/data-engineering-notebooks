## data-engineering-notebooks
Curated list of data pipelines used to showcase datasets across domains

#### Pre-requisites
- Python 3.x+
- Jupyter Lab

#### Quick Setup
The project uses [Pip](https://pypi.org/project/pip/) to keep track of its dependencies. To install it, you can follow the instructions [here](https://pip.pypa.io/en/stable/installation/).

Once Pip has been installed, you can run the following commands to set up the project in your local:
```bash
git clone git@github.com:nathanbaleeta/data-engineering-notebooks.git

python3 -m venv venv

source venv/bin/activate

pip install --quiet pandas requests jupterlab
```
##### To freeze the libaries use:
```
pip freeze > requirements.txt
```
##### #### Install packages from frozen file
```
pip install -r requirements. txt
```
#### Launch notebook
```
jupyter lab 
```
