# datafun-07-ml
Project 7 aims to employ a type of supervised learning, simple linear regression, to train a model using all available data and use the resulting model (a "best-fit" straight line) to make predictions.

## Create Project Virtual Environment

On Windows, create a project virtual environment in the .venv folder. 

```shell

py -m venv .venv
.venv\Scripts\Activate
py -m pip install pyarrow pandas requests jupyterlab matplotlib seaborn

```
## Freeze Requirements

```shell
py -m pip freeze > requirements.txt
```

## Git add and commit 

```shell
git add .
git commit -m "add .gitignore, cmds to readme"
git push origin main
```
