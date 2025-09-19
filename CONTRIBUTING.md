# Contributing

## Handling Python Dependencies

We work with a **requirements.txt** file to manage all Python dependencies.

### Updating Dependencies
To create an up-to-date snapshot of all installed packages, run:
```shell
pip freeze > requirements.txt
```
### Installing Dependencies

To install the dependencies listed in requirements.txt, run:

```shell
pip install -r requirements.txt
```
## Handle Credits

This command extracts all packages from **requirements.txt**.
```shell
pip-licenses --output-file CREDITS.md --format=markdown --with-urls --with-authors --with-description
```