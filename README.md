# 3ds_vscode_template

A ready-to-use VS Code template for Nintendo 3DS homebrew development, providing a pre-configured environment to get started quickly.

## Features

- **VS Code configuration** — Pre-configured `.vscode` settings for Linux/macOS and Windows
- **Hello World starter** — A minimal working example with a simple Makefile to get you up and running
- **IntelliSense support** — Includes a fix so VS Code correctly resolves header definitions
- **CI/CD workflow** — GitHub Actions script to automatically build the project with docker

## Setup configuration on your project

1. Clone this repository
2. Open the folder and copy and paste .vscode in your project folder

## Setup CI Workflow

1. Clone this repository
2. Open the folder and copy and paste `.github` into your project folder
3. To test locally, we use [`act`](https://github.com/nektos/act) — make sure it is installed
4. Run `act push`

## Requirements

- [devkitPro](https://devkitpro.org/) with 3DS support (`ctrulib`)
- [act](https://github.com/nektos/act) — for running GitHub Actions locally
- Visual Studio Code
