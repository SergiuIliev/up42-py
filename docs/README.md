# up42-py docs

Live on github pages:
[https://up42.github.io/up42-py/](https://up42.github.io/up42-py/)

## Installation for doc development:
```
cd docs
pip install -r requirements_docs.txt
```

## HTML Preview Server
Directly integrated in mkdocs, automatically reloads when you edit a file.
```
mkdocs serve
```
Access at `http://127.0.0.1:8000/`

## Update Python API reference preview via mkdocstrings
Reinstall Python package via 
```
pip install -e .
```

## Publish
```
mkdocs gh-deploy
```
Pushes to the `gh-deploy` branch and republishes as github pages.

For more infos see readme here:
https://github.com/up42/docs_mkdocs
