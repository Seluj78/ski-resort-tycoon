# [Ski Resort Tycoon]

* [What is it](#what-is-it)
* [Installation](#installation)
   * [Locally](#locally)
      * [Create a virtual environment](#create-a-virtual-environment)
      * [Activate it](#activate-it)
      * [Install the requirements](#install-the-requirements)
      * [Edit the env file with the correct parametters](#edit-the-env-file-with-the-correct-parametters)
      * [Run the app](#run-the-app)
   * [Deployment on prod or preprod](#deployment-on-prod-or-preprod)
      * [On PREPROD](#on-preprod)
      * [On PROD](#on-prod)
* [Debugging](#debugging)
* [Repository rules](#repository-rules)
* [Code owner](#code-owner)


## What is it

My attempt at creating a 2D, maybe 3D ski resort tycoon game, using the [Arcade](https://arcade.academy/) library.

## Installation

### Locally

#### Create a virtual environment
```shell
python3.11 -m venv venv
```

#### Activate it
```shell
source venv/bin/activate
```

#### Install the requirements
```shell
pip install -r requirements.txt
```

```
pre-commit install
pre-commit install --hook-type commit-msg
```
