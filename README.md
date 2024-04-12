# Title Sort

## Description
Mini-project for sorting titles of media by category using ML.

## Implementation
The first draft sorts patent titles by category based on word similarity using w2v word embeddings.

The second draft uses OpenAI's API to categorize the patent titles.

## Virtual Environment (1st draft)
python3 -m venv ENV_DIR
. ./venv/bin/activate
pip freeze >requirements.txt
pip install -r requirements.txt
deactivate

## Conda Environment (2nd draft)
conda create --name <myenv> --file conda-spec-file.txt