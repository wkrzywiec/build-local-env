# Build local env scripts

This repository holds scripts that installs the most important tools for my daily work.

It requires a Taskfile to be installed: https://taskfile.dev

## Usage

To check list of available tasks run:

```
task --list
```

Exemplary output:

```bash
task: Available tasks for this project:
* linux:brew:           Install Homebrew
* linux:info:           Get info on Linux Os
* linux:kubernetes:     Install kubectl, Helm and Kubernetes in Docker
* linux:pyenv:          Install PyEnv
* linux:python:         Install Python, version: 3.10.3
* windows:info:         Get info on Windows OS
```