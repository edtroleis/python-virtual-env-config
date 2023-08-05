# Python virtual environment

## Description

Creating Python virtual enviroment on Ubuntu. Virtual env is a good approach to isolate libraries and dependencies belong to your project. You can set or replicate Python environment without conflicts, using correct libraries versions and dependencies of your project.

## Install python3-venv on Ubuntu

```bash
apt update
apt install python3.8-venv -y
```

## Create python project

```bash
mkdir project_name
cd project_name
```

## Create virtual env. Default name is venv

```bash
python3 -m venv virtual_env_name
```

## Enable virtual env

```bash
source virtual_env_name/bin/activate
```

## Clone environments

```bash
pip freeze > requirements.tx
```

## Install cloned environment

```bash
pip install -r requirements.txt
```

## Disable virtual env

```bash
deactivate
```

# References

https://docs.python.org/3/library/venv.html
