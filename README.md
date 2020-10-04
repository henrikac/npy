# npy

A simple script to create new [Python](https://www.python.org/) projects and activate virtual environments.

A new project will contain:
+ README.md file
+ Empty .gitignore file
+ Git
+ A virtual environment

## Install
+ Run the install script: `bash ./install`

## Usage:
+ To create a new project: `source npy <project-name>`.
+ To activate a virtual environment: `source svenv <virtual-environment-name>`

To get rid of *source* simply add `alias npy="source npy"` and `alias svenv="source svenv"` to your `.bashrc` file.
