<p align="center"><img width=20% src="https://github.com/zhuhanming/cvwo/blob/master/assets/logo.png" /></p>
<h1 align="center">Hit Your Targets</h1>
<h3 align="center">A todo list for the meticulous</h2>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[![Netlify Status](https://api.netlify.com/api/v1/badges/e702b129-4d70-4b36-afaf-f8f015c62f92/deploy-status)](https://app.netlify.com/sites/eloquent-visvesvaraya-83fcf0/deploys)
<p align="center">Preview the app <a href="https://www.hityourtargets.xyz">here</a></p>

## Basic Overview
A todo list that revolves around task and subtask management, Hit Your Targets aims (pun intended) to fill the gap in the market, and be a precise tool for users to plan every single detail of their life out. Armed with three different views for users organise their day to day activities, Hit Your Targets guarantees to help you, well, hit **your** targets.

<p align="center"><img width=40% src="https://github.com/zhuhanming/cvwo/blob/master/mockups/main-light.png" />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img width=40% src="https://github.com/zhuhanming/cvwo/blob/master/mockups/main-dark.png" /></p>

### Upcoming Features
* Kanban View
* Calendar View

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
