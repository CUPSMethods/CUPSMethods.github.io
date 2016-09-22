---
layout: post
title: 'How I Learned to Let Go and Love Python: An R Story'
tag:
- jupyter notebook
- homebrew
- Python
- R
---

*Presenters: Joe Sutherland*

[Link to the original post](http://jlsutherland.com/essential-hacking/2016/09/22/jupyter-notebook.html)

> It’s not always easy to let go, but in this case the reward far outweighs the risk! The purpose of this session is to introduce the ways in which Python supplants or supplements R in political science research. We will configure Python and Jupyter Notebook on your system, review package management, and collaborate to rewrite a commonly used R script in Python.

### Setup Instructions

1. Install [Homebrew](http://brew.sh) if you're on a Mac, or [Chocolatey](https://chocolatey.org/) if you're on a PC by following the instructions at their homepages.
2. Install the Python distribution. This will also install Python's package manager, `pip`.
  * Mac: `brew install python python3`.
  * PC: `choco install python python3` (run as administrator).
3. Use `pip` to install jupyter notebook.
  * Mac: `pip install jupyter`.
  * PC: `pip install jupyter` (run as administrator).

### Booting Jupyter notebook

To boot the notebook, simply: `jupyter notebook` (on PC it is sometimes `jupyter notepad`) from the command line.

