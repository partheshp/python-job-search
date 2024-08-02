# AI-based Remote Job search

Find your next remote job using a little bit of Python and machine learning!

This tool is based on RemoteOK API and makes it possible to get job recommendations based on your preferences.

## Installation

Use Poetry to install and run commands:
```bash
poetry install
poetry shell
```

## Usage

The program is a CLI application that exposes fetch-new, label, train and recommend commands:

```bash
# fetch new job posts from RemoteOk
python main.py fetch-new

# start data labelling
python main.py label

# train classifier on labeled data
python main.py train

# display recommended jobs
python main.py recommend
```

