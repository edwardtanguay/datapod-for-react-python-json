# datapod-for-react-python-json

This is a simple datapod template for a local site that displays data from a JSON file, which is created by a Python script that parses a text file.

## Howto

https://tanguay-eu.vercel.app/howtos/900

## Video

https://www.youtube.com/watch?v=nbTz9xn9s_U

## Create HTML documentation for qtools

-   cd scripts
-   `pdoc qtools --output-dir docs`
-   see scripts/docs/index.html

## Compatibility

-   ✔️ tested on Windows
-   ✔️ tested on Ubuntu

## Testing

-   `npm test` (runs all pytests)

## Setup

-   (root directory of this project)
-   `python -m venv .venv`
-   (Linux/Mac) `source .venv/bin/activate`
-   (Windows with bash) `source .venv/Scripts/activate`
-   (Windows command line) `.venv\Scripts\activate`
-   `pip install -r requirements.txt`

## Run scripts

-   `python main.py`

## Run Jupyter notebooks example

-   `cd ex_heatmap`
-   `python -m ipykernel install --user --name=.venv --display-name "Python (.venv)"`
-   `jupyter lab`

## More Datapod templates and sites

https://datapod-tanguay-eu.vercel.app
