# node-project

> Configuration files for Node projects


# Overview

A collection of opinionated defaults that ensure consistent, versioned configuration settings across projects.


# Installation

```bash
npm install @timkendrick/node-project
```


# Usage

Add symbolic links to the required files, as follows:

```bash
CONFIG_PATH=node_modules/@timkendrick/node-project

ln -s $CONFIG_PATH/.editorconfig .editorconfig
ln -s $CONFIG_PATH/.eslintrc .eslintrc
ln -s ../../$CONFIG_PATH/git-hooks/pre-push .git/hooks/pre-push
```
