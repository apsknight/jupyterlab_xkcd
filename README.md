# jupyterlab_xkcd

> Show a random xkcd.com comic in a JupyterLab panel.

<img src="http://preview.ibb.co/bxVmrH/Screenshot_from_2018_02_06_20_06_01.png" alt="xkcd comic on Jupyterlab">

## Prerequisites

* JupyterLab

## Installation

```bash
jupyter labextension install @apsknight/jupyterlab_xkcd
```

## Development

For a development install (requires npm version 4 or later), fork this repository and do the following in the home directory:

```bash
git clone https://github.com/<YOUR_USER_NAME>/jupyterlab_xkcd.git
cd jupyterlab_xkcd
npm install
npm run build
jupyter labextension link .
```

To rebuild the package and the JupyterLab app:

```bash
npm run build
jupyter lab build
```

## LICENSE

[MIT](http://aps.mit-license.org)