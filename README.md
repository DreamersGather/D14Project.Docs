# D14Project Documentation

[![Documentation Status](https://readthedocs.org/projects/d14project/badge/?version=latest)](https://d14std.io/en/latest/?badge=latest)

<img src="https://media.githubusercontent.com/media/DreamersGather/D14Docs.Res/main/logo.png" height="82"/>

This repository maintains the overview documentation of D14 series projects.

## Edit

We have included `.vscode` directory in the repository, and thus it is recommended to use VS Code to edit the documentation. In addition, it is convenient to preview every page with **reStructuredText** extension installed in VS Code.

## Build

Install dependencies (`requirements.txt` is located in the root directory of the project):

```
> pip install sphinx
> pip install -r requirements.txt
```

Generate documentation:

```
> make html
```

Open documentation (in the default browser):

```
> make open
```

## About

The two Chinese characters "文档" (means documentation) in the logo are in 小篆 (a font called Small Seal Script). After unifying the six states, Emperor Qin Shi Huang implemented the policy of "书同文" (writing with the same script), and 小篆 was selected as the written script widely used throughout the country. As a special type of information, we believe that documentation is playing a role in unifying the existing knowledge of the related project.
