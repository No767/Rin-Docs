# Rin Docs ![Read the Docs](https://img.shields.io/readthedocs/rin-docs?logo=read-the-docs)

Documentation for the Rin bot. This repo is published to ReadTheDocs, which can be found [here](https://rin-docs.readthedocs.io/en/latest/)

## Building

### Environment Setup

Before you start, you'll need to set up your Python environment. 

1. Install [Python 3](https://www.python.org/)
2. Install [MkDocs](https://www.mkdocs.org/)
3. Install all other dependencies (they are listed within the requirements.txt file)

Once installed, run this cmd to install the other packages:

` $ pip install -r requirements.txt`


### Compiling

This docs uses MkDocs, so all you need to is to run `mkdocs serve` in order to get a live webserver, make the adjustments, and commit to the repo. This uses .md files instead of .rst files
