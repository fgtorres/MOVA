![](https://github.com/fgtorres/MOVA/blob/main/assets/img/logo.png)

# MOVA - A tool for public movie data analytics

## Introduction

The increase in movie streaming services in recent years indicates a new opportunity for the entertainment market. There are several databases and public metadata services for content such as movies and series, for example MovieDB. This data can assist in the discovery of knowledge based on machine learning in the face of metadata and consumption.Thinking about this opportunity, a library of knowledge discovery in movie and series data called MOVA was created.

## Installation

The MOVA is a Python library that uses:
*  PrettyPrinter
*  json
*  pandas
*  sklearn
*  numpy

1°)For install this library use the CLI command below:

``
pip install prettyprinter,json,pandas,sklearn,numpy 
``

2°)The next step is to set up a access keys of sources on settings path, creating a new file with filename "APIKeys.py". The contents of this file must be:

```
apiKeyOMDB = ''
apiKeyWatchMode = ''
apiKeyTMDB = ''
```

3°) Just run it!

``
python MovaCLI.py 
``

