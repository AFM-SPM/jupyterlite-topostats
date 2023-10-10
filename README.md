# JupyterLite TopoStats

[![lite-badge](https://jupyterlite.rtfd.io/en/latest/_static/badge.svg)](https://jupyterlite.github.io/demo)

This repository contains a series of Notebooks for processing and summarising images from Atomic Force Microscopy (AFM)
using the Python package [TopoStats](https://afm-spm.github.io/topostats) (Git Repository :
[AFM-SPM/TopoStats](https://github.com/AFM-SPM/TopoStats)).

The Notebooks are deployed using [JupyterLite](https://jupyterlite.readthedocs.io/en/latest/) which uses the
[Pyodide](https://pyodide.org/en/stable/) implementation of Python which is written in
[WebAssembly](https://webassembly.org/). This means the Notebooks run completely in your browser, there is no need to
install Jupyter on your computer.

You will find that the initial loading takes a little while as the necessary Python packages, TopoStats and all its
dependencies, are downloaded and installed. Subsequent visits should be quicker though as these are cached (if you clear
your cache they will need downloading again).

## Requirements

JupyterLite is being tested against modern web browsers:

- Firefox 90+
- Chromium 89+

## ✨ Try it in your browser ✨

➡️ **https://afm-spm.github.io/jupyterlite-topostats**

The Notebooks are commented and should provide a walk-through of the various steps involved in loading and filtering raw
images and then detecting grains, tracing them and calculating statistics. There are also example Notebooks that show
how to plot both the image scans at various stages and the resulting statistics.

## Contributing

For more info, keep an eye on the JupyterLite documentation:

- [How-to Guides](https://jupyterlite.readthedocs.io/en/latest/howto/index.html)
- [Deployment](https://jupyterlite.readthedocs.io/en/latest/quickstart/deploy.html)
- [Reference](https://jupyterlite.readthedocs.io/en/latest/reference/index.html)
