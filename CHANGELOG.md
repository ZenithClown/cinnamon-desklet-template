# Changelog

<p align = "justify">All notable changes to this <code><b>cinnamon-desklet-template</b></code> will be documented here. The format is based on <a href = "https://keepachangelog.com/en/1.0.0/">Keep a Changelog</a>, and this project adheres to <a href = "https://semver.org/spec/v2.0.0.html">Semantic Versioning</a>.</p>

## [v1.0.0](https://github.com/ZenithClown/cinnamon-desklet-template/releases/tag/v1.0.0)
<p align = "justify">Basic cookiecutter template with bare-minimum files required for creating a cinnamon desklet application. A desklet project can be initialized from the terminal with the command: <code>cookiecutter https://github.com/ZenithClown/cinnamon-desklet-template</code>. On initialization, the following project structure is produced:</p>

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
