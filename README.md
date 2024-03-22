# django-community-playground
A sample project to test things out


## Running tests

```shell
python -m unittest
```

## Manually building and uploading

```shell
python3 -m pip install -U twine build
python3 -m build
python3 -m twine upload --repository testpypi dist/*
```
