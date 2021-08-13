# Rin Docs 

<a href='https://rin-docs.readthedocs.io/en/latest/?badge=latest'>
    <img src='https://readthedocs.org/projects/rin-docs/badge/?version=latest' alt='Documentation Status' />
</a>

Documentation for the Rin bot. This repo is published to ReadTheDocs, which can be found [here](https://rin-docs.readthedocs.io/en/latest/)

## Building

### Environment Setup

Before you start, you'll need to set up your Python environment. 

1. Install [Python 3](https://www.python.org/)
2. Install [MkDocs](https://www.mkdocs.org/)
3. Install all other dependencies (they are listed within the requirementst.txt file)

Once installed, run this cmd to install the other packages:

` $ pip install -r requirements.txt`


### Building

This docs uses MkDocs, so all you need to is to run `mkdocs serve` in order to get a live webserver, make the adjusts, and commit to the repo. This uses .md files instead of .rst files