Flexx
=====

[![CI](https://github.com/flexxui/flexx/workflows/CI/badge.svg)](https://github.com/flexxui/flexx/actions)
[![Documentation Status](https://readthedocs.org/projects/flexx/badge/?version=latest)](https://flexx.readthedocs.org)
[![PyPI version](https://badge.fury.io/py/flexx.svg)](https://badge.fury.io/py/flexx)

Want to stay up-to-date about (changes to) Flexx? Subscribe to the [NEWS issue](https://github.com/flexxui/flexx/issues/477).


## Project Overview

[Flexx](https://flexx.readthedocs.io) is a pure Python toolkit for creating graphical user interfaces (GUI's), that uses web technology for its rendering. Apps are written purely in Python; the [PScript](https://pscript.readthedocs.io) transpiler generates the necessary JavaScript on the fly.

Flexx can be used to create (cross-platform) desktop applications, web applications, and export apps to standalone HTML documents. It also works in the Jupyter notebook.

The docs are on [Readthedocs](http://flexx.readthedocs.io). The code is on [Github](http://github.com/flexxui/flexx).

### Motivation

The web has become a popular method for delivering applications, including interactive scientific content. Flexx provides a single framework for creating desktop applications, web apps, and potentially mobile apps using browser technology, making it widely available and easy to use.

## Prerequisites

Flexx requires Python 3.5+ and works on PyPy. The following dependencies are required:
- [Tornado](http://www.tornadoweb.org) (pure Python library)
- [PScript](http://github.com/flexxui/pscript) (pure Python library)
- [Webruntime](http://github.com/flexxui/webruntime) (pure Python library)
- [Dialite](http://github.com/flexxui/dialite) (pure Python library)

Supported browsers include Firefox, Chrome, and Edge. Internet Explorer 10+ should work but may have some issues. For desktop apps, Firefox or NW.js is required.

## Installation

### Option 1: Install Latest Release
Run the following command:
```bash
pip install flexx
```

### Option 2: Install Latest from GitHub
Run the following command:
```bash
pip install -U https://github.com/flexxui/flexx/archive/master.zip
```

### Verification
To verify the installation, check the library version with:
```bash
pip show flexx
```

## Example

Click the image below for an interactive example:

[![demo](https://dl.dropboxusercontent.com/s/x4s7wgv6tpyqsqo/flexx_demo_300.png)](http://flexx.readthedocs.io/en/latest/examples/demo_src.html)

## A Word of Caution

Flexx is versatile and allows mixing Python code running on the server with code running in the browser. While this is powerful, it can lead to maintenance challenges. Developers should clearly separate Python and PScript code.

## External Documents

For more information, refer to the [documentation](https://flexx.readthedocs.io) and related resources and CONTRIBUTING.md.

## License

Flexx uses the liberal 2-clause BSD license. See LICENSE for details.
