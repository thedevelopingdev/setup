# Setting up Paperspace

## Notebooks

#### 1. Use `bash`

In a terminal, simply type the command `bash` to use `bash` as the shell.

#### 2. Install `nvm` (Node version manager) and the latest version of Node

```sh
$ curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.36.0/install.sh | bash

$ nvm ls-remote
$ nvm install <latest LTS version>
```

- Source: [Github: nvm-sh/nvm](https://github.com/nvm-sh/nvm)

#### 3. Install `vim` extensions for Jupyterlab

```sh
$ jupyter labextension install jupyterlab_vim
```

- Notes: requires Node.js and npm.
