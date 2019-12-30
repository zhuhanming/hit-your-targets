# Hit Your Targets - A todo list for the meticulous
[![Netlify Status](https://api.netlify.com/api/v1/badges/e702b129-4d70-4b36-afaf-f8f015c62f92/deploy-status)](https://app.netlify.com/sites/eloquent-visvesvaraya-83fcf0/deploys)

Preview the app [here](https://www.hityourtargets.xyz)

## Cloning this repository
Note that git repositories with submodules are handled differently by git and cannot be cloned directly. Please use the command

```git
git clone --recursive https://github.com/zhuhanming/cvwo.git
```
to clone this repository.

If you have already cloned the repository without the `--recursive` flag, you might find that the submodule folders are empty. To fix that, run

```git
git submodule update --init --recursive
```
in the repository folder to pull the submodules.

### READMEs
The various READMEs can be found in their respective folders.

This repository consists of three submodules:

1. `hit-your-target-frontend` contains the code for the frontend, hosted at [https://www.hityourtargets.xyz](https://www.hityourtargets.xyz)
2. `hit-your-target-api` contains the code for the backend, hosted at [https://radiant-sea-97785.herokuapp.com](https://radiant-sea-97785.herokuapp.com)
