# Description
Convert 5 objects into a comma separated list
Object type will be put in by the user

# Packages used
1. openai
2. langchain
3. python-dotenv

# Create project
## Installations prerequisites
install conda
pip install python-dotenv
pip install openai
pip install langchain

## Steps to create project
conda create -n convert_list python=3.11
conda activate convert_list
pip install poetry
### Create a pyproject.toml file
poetry init 
poetry install     