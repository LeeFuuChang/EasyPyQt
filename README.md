# EasyPyQt Overview
---

EasyPyQt reads a .ui file create by QtDesigner. 
It analyzes through the xml structure to discover every widget you used,
and then generate runnable python code based on it.
The python code generated is immediately runnable, and can be generated in both module and file form.


## Why?
---

The module is created for school educational usage.
For teenagers and kids to quickly create a runnable project, without having to write lots of code,
so they won't lose interest nor get scared by the coding process.


## Installation
---

EasyPyQt is available on PyPI. You can install it through `pip`:

```bash
pip install EasyPyQt
```

Usage
---

Basic usage is very simple, just run it against your .ui file:

```bash
epyqt /path/to/yourUIfile.ui
```

Get help and full usage:

```bash
epyqt
epyqt -h
epyqt --help
```

