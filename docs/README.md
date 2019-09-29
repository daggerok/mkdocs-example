# mkdocs-example
Generate material design documentation: [![Build Status](https://travis-ci.org/daggerok/mkdocs-example.svg?branch=master)](https://travis-ci.org/daggerok/mkdocs-example)

```bash
mkdir -p mkdocs-example
cd mkdocs-example/

pip3 install --upgrade pip
pip3 install mkdocs
mkdocs --version
# output: mkdocs, version 1.0.4 from /Users/user/.homebrew/lib/python3.7/site-packages/mkdocs (Python 3.7)
pip3 install --upgrade mkdocs-material
pip3 install --upgrade mkdocs-minify-plugin

mkdocs serve
# ...
mkdocs build
```
