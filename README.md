# node-project

> Configuration files for Node projects


## Installation

```bash
npm install @timkendrick/node-project
```


## Overview

A collection of opinionated defaults that ensure consistent, versioned configuration settings across projects.


## Included files

This package creates symbolic links for the following files, if they do not already exist:

- `.editorconfig`: [EditorConfig](http://editorconfig.org/) configuration
- `.eslintrc`: [ESLint](http://eslint.org/) configuration
- `.git/hooks/pre-push`: Git pre-push hook that runs `npm test` before pushing
