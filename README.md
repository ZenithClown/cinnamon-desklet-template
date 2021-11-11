<h1 align = "center">
    Cinnamon Desklet Template <br>
    <sub><b><i>(python, docker, rest-api, flake8)</i></b></sub> <br>
    <a href = "https://www.linkedin.com/in/dpramanik/"><img height="16" width="16" src="https://unpkg.com/simple-icons@v3/icons/linkedin.svg"/></a>
    <a href = "https://github.com/ZenithClown"><img height="16" width="16" src="https://unpkg.com/simple-icons@v3/icons/github.svg"/></a>
    <a href = "https://gitlab.com/ZenithClown/"><img height="16" width="16" src="https://unpkg.com/simple-icons@v3/icons/gitlab.svg"/></a>
    <a href = "https://www.researchgate.net/profile/Debmalya_Pramanik2"><img height="16" width="16" src="https://unpkg.com/simple-icons@v3/icons/researchgate.svg"/></a>
    <a href = "https://www.kaggle.com/dPramanik/"><img height="16" width="16" src="https://unpkg.com/simple-icons@v3/icons/kaggle.svg"/></a>
    <a href = "https://app.pluralsight.com/profile/Debmalya-Pramanik/"><img height="16" width="16" src="https://unpkg.com/simple-icons@v3/icons/pluralsight.svg"/></a>
    <a href = "https://stackoverflow.com/users/6623589/"><img height="16" width="16" src="https://unpkg.com/simple-icons@v3/icons/stackoverflow.svg"/></a>
</h1>

<p align = "justify">A simple <code>cookiecutter</code> template for Cinnamon Desklet Application. "Desklets are little programs which you can place on your desktop, on top of your desktop background." <a href = "https://cinnamon-spices.linuxmint.com/">[1]</a>. A desklet is written in JavaScript, and the minimalistic template is provided here. The template contains the following file(s) for ready reference:</p>

- `.gitignore` - generated from [toptal](https://www.toptal.com/developers/gitignore).
- `.gitattributes` - to map specific data types which might be used in this repository.
- `README.md` - a file that contains information about the repository (you're reading the file!)
- `CHANGELOG.md` - All notable changes are defined here.

<p align = "justify">You're free to use and edit any of the files in this repository, even for commercial use. Do include reference to this repository using any of the specified method (or create your own). Also, note that the repository uses <code>markdown</code> so feel free to use the same, or change to an alternative like <code>rich text format</code> as required.</p>

* **`[generated from template](https://github.com/ZenithClown/cinnamon-desklet-template)`**
* **```<a href="https://github.com/ZenithClown/cinnamon-desklet-template">generated from template</a>```**

## Quick Start Guide
<p align = "justify">The template is built to be used by <a href = "https://cookiecutter.readthedocs.io/en/1.7.3/README.html"><code>cookiecutter</code></a> - an excellent command-line utility to initialize a project from a template.</p>

### Prerequisite
<p align = "justify">Considering base level cinnamon flavored system, you will first need to install <code>pip</code> followed by cookiecutter installation (check python version requirement for cookiecutter at <a herf = "https://cookiecutter.readthedocs.io">documentation</a>).</p>

```bash
$ sudo apt install -y python3-pip
$ pip install cookiecutter
```

### Creating a Project from Remote URL
<p align = "justify">Once the utility is installed, initiate a project with <code>cookiecutter https://github.com/ZenithClown/cinnamon-desklet-template</code>, this will ask a series of questions to initialize the directory as follows.</p>

```shell
~/.local/share/cinnamon/desklets > cookiecutter https://github.com/ZenithClown/cinnamon-desklet-template                                                        21:43:22
project_name [My Projetc]: hello-world
author_name [ZenithClown]: 
UUID [hello-world@ZenithClown]: 
description [A short description of hello-world.]: A hello world cinnamon desklet application.  
prevent_decorations [Prevent Desklet Decorations (true/false)?]: true
~/.local/share/cinnamon/desklets > cd hello-world@ZenithClown                                                                                             1m 8s 21:44:48
~/.local/share/cinnamon/desklets/hello-world@ZenithClown > tree -ah                                                                                             21:44:56
.
├── [   0]  CHANGELOG.md
├── [4.0K]  hello-world@ZenithClown
│   ├── [  78]  desklet.js
│   └── [ 174]  metadata.json
├── [ 174]  info.json
└── [   0]  README.md

1 directory, 5 files
```

An example of *"hello world"* desklet application is available at [this link](https://github.com/ZenithClown/hello-cinnamon-desklet). Note, if creating for local then `desklet.js` and `metadata.json` has to be present in root directory (i.e. unless published).
